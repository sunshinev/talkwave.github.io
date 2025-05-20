# FAQ

<div class="support-container">
<div class="button-group">

> Need direct assistance? Our support team responds within 24 hours to all inquiries about account issues, troubleshooting, or general questions.


  <a href="mailto:talkwave.fun@gmail.com" class="action-btn purple">
    <i class="fas fa-envelope"></i>
    Email Support
  </a>

> Share your suggestions or report bugs through our structured form. Your feedback helps us improve TalkWave's features and user experience.


  <a href="https://tally.so/r/mOVvD8" class="action-btn blue" target="_blank">
    <i class="fas fa-comment-alt"></i>
    Feedback Form
  </a>
</div>

<iframe src="/app/docs/#/faq" class="faq-frame"></iframe>
</div>

<style>
/* 按钮样式增强 */
.action-btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  padding: 14px 28px;
  margin: 12px;
  border-radius: 10px;
  font-weight: 500;
  text-decoration: none !important;
  transition: all 0.3s ease;
  border: 2px solid transparent;
}

.action-btn.purple {
  background: #6D31ED;
  color: white !important;
  box-shadow: 0 4px 6px rgba(109, 49, 237, 0.2);
}

.action-btn.blue {
  background: #007AFF;
  color: white !important;
  box-shadow: 0 4px 6px rgba(0, 122, 255, 0.2);
}

.action-btn:hover {
  transform: translateY(-2px);
  opacity: 0.9;
}

/* 框架样式 */
.faq-frame {
  width: 100%;
  height: 600px;
  border: 1px solid rgba(109, 49, 237, 0.2);
  border-radius: 12px;
  margin-top: 20px;
  background: rgba(255,255,255,0.05);
}

/* 响应式布局 */
@media (max-width: 768px) {
  .button-group {
    display: flex;
    flex-direction: column;
  }
  
  .action-btn {
    width: calc(100% - 24px);
    margin: 8px 12px;
    justify-content: center;
  }
  
  .faq-frame {
    height: 400px;
  }
}
</style>