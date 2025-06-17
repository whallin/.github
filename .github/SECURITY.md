# Security Policy

Security might sound serious (and it is!), but that doesn't mean we can't talk about it in a friendly way. Think of this as my digital security approach — I want to keep my projects and users safe while maintaining an open and welcoming environment.

Whether you're contributing to my public open-source projects or just using them, this guide covers how I handle security. I believe that good security comes from clear communication, transparency, and a healthy dose of common sense.

## 🔐 What I'm protecting

My security efforts cover everything that makes my projects work:

- **Public repositories:** Open source projects that anyone can see and contribute to.
- **Personal projects:** Side projects, experiments, and work-in-progress code.
- **User data:** Any personal information, authentication credentials, and private communications in my projects.
- **Infrastructure:** Servers, databases, CI/CD pipelines, and deployment environments.
- **Access control:** Making sure the right people have access to the right things at the right time.

> [!NOTE]
> Security isn't just about keeping bad actors out — it's about building trust with users and contributors while maintaining a secure development environment.

## 🚨 Found a security flaw?

First things first, thank you! Security researchers and users who report issues are absolute heroes in my book. I take every report seriously and promise to work with you to resolve them quickly.

- ❌ Please **don't** create a public issue, post on social media, or share details publicly until I've had a chance to fix things. I know you want to help, but public disclosure can put users at risk.
- ✅ Please **do** send me a private heads-up so we can work together on a solution.

### How to reach me

**📧 Primary contact:** Send your security reports to [william@hallin.media](mailto:william@hallin.media). I check this email regularly throughout the day, so you'll get an acknowledgment within 24 hours (usually much faster!), and I'll keep you updated throughout the process.

**🚨 For urgent issues:** If you've found something that puts users in immediate danger, include "URGENT - SECURITY" in your subject line. I'll prioritize investigating it right away.

### What to include in your report

Help me help you (and everyone else) by including:

**📋 The basics:**

- A clear description of the vulnerability.
- Which repository or service is affected.
- Your assessment of the potential impact.

**🔄 Steps to reproduce:**

- Detailed steps we can follow to see the issue.
- Screenshots or videos if they help explain things.
- Any proof-of-concept code (if you have it)

> [!TIP]
> The more detail you give me, the faster we can fix things!

## 🔎 My investigation process

Here's what happens after you report an issue:

1. **Initial response:** I'll confirm I got your report and start investigating right away.
2. **Assessment:** I'll reproduce the issue, assess the impact, and determine the severity level.
3. **Coordination:** I'll keep you in the loop as I develop a fix. This is a collaborative effort!
4. **Resolution:** Once I've deployed the fix, I'll let you know and coordinate any public disclosure.
5. **Recognition:** With your permission, I'll give you credit for the discovery (unless you prefer to stay anonymous — that's totally fine!).

## 🎯 Responsible disclosure

I believe in coordinated disclosure because it protects everyone:

**🤝 My commitment to you:**

- I'll acknowledge your report quickly and keep you updated.
- I won't pursue legal action for good-faith security research.
- I'll work with you on disclosure timing that's fair for everyone.
- I'll give you credit (if wanted) when I publish the fix.

**🙏 What I hope you'll do:**

- Give me reasonable time to investigate and fix issues.
- Avoid accessing data that isn't yours or disrupting my services.
- Let me coordinate public disclosure to protect users.

Generally, I aim to fix critical issues within 7 days, high-severity issues within 30 days, and everything else within 90 days. Complex issues might take longer, but I'll keep you posted.

## 🛠️ Security best practices for contributors

Whether you're contributing to my public repositories or just using them, here are security habits that make everyone's lives easier and safer:

**🔒 Keep secrets secret:**

- Never commit API keys, passwords, or other secrets to version control.
- Use environment variables or secure secret management tools.

**📦 Dependencies matter:**

- Keep your dependencies up to date.
- Run security scans regularly (my CI/CD does this automatically).
- Be thoughtful about adding new dependencies.

**👀 Code reviews are security reviews:**

- Look for potential security issues during code review.
- Ask questions if something seems risky.
- Remember: it's easier to prevent problems than fix them later.

### For open-source contributors

**🍴 Fork safely:**

- Don't add sensitive configuration to public forks.
- Be mindful of what you're exposing in your development environment.

**🧪 Testing and development:**

- Use test data, never real user data.
- Be careful with local development setups.
- Report any security concerns you notice during development.

## 📞 Frequently asked questions

**Q: What if I'm not sure if something is a security issue?**

A: When in doubt, report it! I'd rather investigate a false alarm than miss a real issue.

**Q: Can you help me secure my own fork or deployment?**

A: While I can't provide individual consulting, my documentation includes security best practices, and I'm always happy to share knowledge when I can.

**Q: Do you have a bug bounty program?**

A: Not currently, as I'm a solo developer, but I'm always grateful for responsible disclosure and will find ways to show my appreciation.

**Q: How do I know if a security update affects me?**

A: I announce security updates through GitHub releases and direct communication when necessary.

**Q: Are you available for security consulting?**

A: I focus on my own projects, but feel free to reach out — I might be able to point you in the right direction!

---

_Got something else on your mind? Email [william@hallin.media](mailto:william@hallin.media) for security inquiries, privacy concerns, or general questions about my projects._
