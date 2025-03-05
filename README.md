# Puzzle CAPTCHA 解题器

[![宣传图片](https://github.com/bright-cn/LinkedIn-Scraper/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner.png)](https://www.bright.cn/products/web-unlocker/captcha-solver/puzzle-captcha)

使用 Bright Data 的先进 CAPTCHA 解决技术，轻松绕过 Puzzle CAPTCHA。利用机器学习算法、[自动 IP 轮换](https://www.bright.cn/solutions/rotating-proxies)和强大的代理基础设施，确保持续无缝地访问目标网站。

Bright Data 的 CAPTCHA Solver 集成在 [**Scraping Browser**](https://www.bright.cn/products/scraping-browser) 和 [**Web Unlocker API**](https://www.bright.cn/products/web-unlocker) 中，为应对最复杂的 CAPTCHA 挑战提供全面解决方案。

## 功能特点  
- **快速解题**：自动且高效地解决 Puzzle CAPTCHA。  
- **IP 轮换**：通过自动重试和动态 IP 调整，避免被封禁。  
- **浏览器指纹模拟**：模仿真实用户行为，[绕过高阶的机器人检测](https://www.bright.cn/blog/web-data/anti-scraping-techniques)。  
- **JavaScript 渲染**：适用于依赖大量 JavaScript 的动态网站。  
- **全球覆盖**：可精确定位至全球任意地区，轻松解锁当地内容。  
- **无缝集成**：与 Puppeteer、Playwright、Selenium 等工具完美兼容。  
- **事件监控**：监测 CAPTCHA 检测、成功以及失败等事件。

## 为什么选择 Puzzle CAPTCHA 解题器

### **全球 20,000+ 客户的信赖**  
Bright Data 的 CAPTCHA Solver 在开发者、企业和大型机构中广受信赖，具备可靠的性能表现。

### **顶级代理网络支持**  
凭借超过 1 亿 IP 地址以及先进的地理定位功能，我们的代理基础设施可确保稳定、持续的 CAPTCHA 解题体验。

### **AI 驱动的 CAPTCHA 解决方案**  
我们的 CAPTCHA Solver 使用先进的 AI 逻辑来检测、分析并自动解决 CAPTCHA，包括重试机制、指纹模拟、头信息处理等多种方式，帮助绕过最困难的反机器人系统。

### **为开发者而生**  
- 可轻松集成到 Puppeteer、Playwright、Selenium。  
- 可高度自定义 CAPTCHA 解题行为。  
- 自动重试与动态 IP 调整，确保爬取过程不间断。

> **专家提示 💡**  
>> 你已有自己的 CAPTCHA 解决方案吗？使用我们针对 [Puppeteer](https://www.bright.cn/integration/puppeteer)、[Playwright](https://www.bright.cn/integration/playwright) 和 [Selenium](https://www.bright.cn/integration/selenium) 的代理服务，减少 CAPTCHA 出现率。

## 运作方式

Bright Data 的 CAPTCHA Solver 已无缝整合在 **Scraping Browser** 和 **Web Unlocker** 中，让解题过程简化到极致。

### **自动 CAPTCHA 解题**  
该解题器会自动实时检测并处理 CAPTCHA。只需启用此功能，它便可从检测到解题全程自动完成。

#### 示例工作流程：  
1. **检测 CAPTCHA**：解题器识别 CAPTCHA 类型（如 PerimeterX）。  
2. **解决 CAPTCHA**：使用 AI 逻辑自动完成解题。  
3. **失败重试**：若解题失败，系统将自动使用新 IP 重试。  
4. **返回结果**：成功通过后，系统将为您提供无缝的目标站点访问。

## 支持的 CAPTCHA 类型

Bright Data 的 CAPTCHA Solver 支持众多 CAPTCHA 类型，包括：

- [**DataDome**](https://www.bright.cn/products/web-unlocker/captcha-solver/datadome)  
- [**reCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/recaptcha)  
- [**Click Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/click-captcha)  
- [**Cloudflare**](https://www.bright.cn/products/web-unlocker/captcha-solver/Cloudflare)  
- [**PerimeterX**](https://www.bright.cn/products/web-unlocker/captcha-solver/perimeterx)  
- [**SimpleCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/simplecaptcha)  
- [**FunCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/funcaptcha)  
- [**Cloudflare Turnstile**](https://www.bright.cn/products/web-unlocker/captcha-solver/cloudflare-turnstile)  
- [**AWS WAF Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/aws-waf-captcha)  
- [**GeeTest CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/geetest-captcha)  
- [**KeyCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/keycaptcha)  
- [**Puzzle CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/puzzle-captcha)  
- [**Yandex CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)  
- [**Image CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/image-captcha)  
- [**Text CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/text-captcha)

## 高级自定义

[Bright Data 的 CAPTCHA Solver](https://github.com/bright-cn/Captcha-solver) 支持精细化自定义，可针对特定场景微调解题逻辑。

### **Puzzle 挑战的自定义选项**  
```javascript
// 为不同类型的 CAPTCHA 定义默认选项
function getCaptchaOptions(captchaType, customOptions = {}) {
  const defaultOptions = {
    timeout: 30000, // 等待 CAPTCHA 解题的最长时间（毫秒）
    check_timeout: 500, // 轮询 CAPTCHA 状态的间隔（毫秒）
    wait_networkidle: { timeout: 1000 }, // 网络空闲 1 秒后再继续
    debug: false // 调试模式（默认关闭）
  };

  // 为不同 CAPTCHA 类型定义相应的选择器
  const captchaSelectors = {
    DataDome: { selector: '#datadome-captcha', success_selector: '#captcha-success' },
    reCAPTCHA: { selector: '.g-recaptcha', success_selector: '.recaptcha-success' },
    ClickCaptcha: { selector: '.click-captcha', success_selector: '.captcha-passed' },
    hCaptcha: { selector: '.h-captcha', success_selector: '.hcaptcha-success' },
    PerimeterX: { selector: '#px-captcha', success_selector: '#px-success' },
    SimpleCaptcha: { selector: '.simple-captcha', success_selector: '.captcha-done' },
    FunCaptcha: { selector: '.funcaptcha', success_selector: '.funcaptcha-success' },
    CloudflareTurnstile: { selector: '.cf-turnstile', success_selector: '.cf-success' },
    AWSWAF: { selector: '#aws-waf-captcha', success_selector: '#aws-waf-success' },
    GeeTest: { selector: '.geetest-captcha', success_selector: '.geetest-success' },
    KeyCAPTCHA: { selector: '#keycaptcha', success_selector: '#keycaptcha-success' },
    PuzzleCAPTCHA: { selector: '.puzzle-captcha', success_selector: '.puzzle-solved' },
    YandexCAPTCHA: { selector: '#yandex-captcha', success_selector: '#yandex-success' },
    ImageCAPTCHA: { selector: '.image-captcha', success_selector: '.image-captcha-success' },
    TextCAPTCHA: { selector: '.text-captcha', success_selector: '.text-captcha-success' }
  };

  // 根据给定的 CAPTCHA 类型获取对应的选择器
  const selectedOptions = captchaSelectors[captchaType] || {};

  // 将默认选项、CAPTCHA 类型对应的选择器以及自定义选项进行合并
  return { ...defaultOptions, ...selectedOptions, ...customOptions };
}

// 不同 CAPTCHA 类型的示例用法
const ddOptions = getCaptchaOptions('DataDome', { timeout: 40000, debug: true });
const recaptchaOptions = getCaptchaOptions('reCAPTCHA', { debug: true });
const hcaptchaOptions = getCaptchaOptions('hCaptcha');

console.log(ddOptions);
console.log(recaptchaOptions);
console.log(hcaptchaOptions);

// 示例错误处理
try {
  if (!document.querySelector(ddOptions.selector)) {
    throw new Error(`未能通过选择器找到 CAPTCHA 元素：${ddOptions.selector}`);
  }

  // 在此处实现您的 CAPTCHA 解题逻辑
  solveCaptcha(ddOptions);
} catch (error) {
  console.error('解题失败：', error.message);
}
```

## **事件监控**  
跟踪以下事件，以管理高级用例：  
- `Captcha.detected`：已检测到 CAPTCHA，并开始解题。  
- `Captcha.solveFinished`：成功解题。  
- `Captcha.solveFailed`：解题失败。

## **价格方案**

| **方案**            | **价格（每 1K 结果）** | **月度费用**       | **说明**                                 |  
|---------------------|------------------------|--------------------|------------------------------------------|  
| **按需付费**        | $1.50                 | 无固定承诺         | 适合零散与临时爬取需求。                 |  
| **Growth**          | $1.27                 | $499               | 面向逐步扩张的团队。                     |  
| **Business**        | $1.12                 | $999               | 适合大规模爬取需求。                     |  
| **Premium**         | $1.05                 | $1,999             | 高级功能与优先支持。                     |  
| **Enterprise**      | 定制报价              | 联系我们           | 为大型企业提供定制方案。                 |  

🚀 **特别优惠**：首次充值最高可获得 **$500** 等额匹配！

## **为什么开发者钟爱 Puzzle CAPTCHA 解题器**  
- **易于集成**：与 Puppeteer、Playwright、Selenium 无缝兼容。  
- **先进的 AI 逻辑**：自动处理重试、CAPTCHA 解题、指纹模拟、IP 轮换和高级头信息。  
- **内置浏览器**：无需手动管理其他浏览器来进行 JavaScript 渲染。  
- **实时洞察**：通过实时仪表盘监控网络性能数据。  
- **一流支持**：全年无休的全球客户支持，每天都在更新新功能。

## **常见问题**

### **Puzzle CAPTCHA 解题器的工作原理是什么？**  
该解题器使用先进的 AI 逻辑自动检测并解决 Puzzle CAPTCHA。

### **它能同时处理多个 CAPTCHA 吗？**  
可以，该方案可同时处理多种 CAPTCHA 类型，保障访问不中断。

### **如果 CAPTCHA 解决失败怎么办？**  
系统会自动进行重试。如果依旧失败，可联系我们 24/7 客服团队以进一步排查。

---

## **告别 Puzzle CAPTCHA 的烦恼**  
立即开始您的免费试用，体验来自 Bright Data 的无缝 [Puzzle CAPTCHA 解题](https://www.bright.cn/products/web-unlocker/captcha-solver/puzzle-captcha)！
