<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

# CONTRIBUTING.md for Code Whisper

## Introduction

Thank you for considering contributing to Code Whisper! This document outlines the process for contributing to our multimodal AI coding assistant that uses screen sharing and voice interaction to help users learn programming through natural conversation.

## Project Overview

Code Whisper is a web-based coding assistant that integrates with your browser to provide real-time guidance through:

- Screen sharing analysis of your code
- Voice-based interaction for questions and explanations
- JavaScript and Python language support
- Integration with a web-based code editor


## Setting Up Your Development Environment

1. **Fork and clone the repository**:

```bash
git clone https://github.com/YOUR-USERNAME/code-whisper.git
cd code-whisper
```

2. **Install dependencies**:

```bash
pip install git+https://github.com/googleapis/python-genai.git
pip install websockets pydub
```

3. **Set up Gemini API key**:
Request access to the Gemini API and set your API key as an environment variable:

```bash
export GOOGLE_API_KEY="your-api-key-here"
```

4. **Start the development server**:

```bash
python server.py
```


## Code Structure

Our codebase is organized into several key components:

- `/backend`: WebSocket server and Gemini API integration
- `/frontend`: Web-based editor and UI components
- `/shared`: Utilities shared between frontend and backend


## Contribution Workflow

### 1. Choose an Issue

- Start with issues labeled "good-first-issue" or "help-wanted"
- Comment on the issue to let others know you're working on it
- If creating a new feature, open an issue first to discuss the implementation


### 2. Create a Branch

```bash
git checkout -b feature/descriptive-branch-name
```


### 3. Development Guidelines

- **Code Style**:
    - Follow PEP 8 for Python code
    - Use ESLint with our configuration for JavaScript
    - Use meaningful variable names and comments
    - Keep functions small and focused on a single responsibility[^2]
- **Commit Messages**:
    - Use clear, descriptive commit messages
    - Reference issue numbers in commits (e.g., "Fix \#42: Improve audio quality")[^9]
    - Make small, focused commits rather than large changes
- **Testing**:
    - Write tests for all new features
    - Ensure existing tests pass before submitting
    - Include both unit and integration tests where appropriate[^6]


### 4. Pull Request Process

1. **Update your branch with the latest changes**:

```bash
git pull origin main
```

2. **Push your changes and create a pull request**:

```bash
git push origin feature/descriptive-branch-name
```

3. **Pull Request Template**:
    - Describe the changes made and their purpose
    - Link to any related issues
    - Include screenshots for UI changes
    - List any dependencies added
    - Document any manual testing performed
4. **Code Review**:
    - All PRs require at least one review
    - Address all reviewer comments
    - Automated tests must pass
    - Be open to constructive feedback[^3]

## Special Considerations for AI Components

### Screen Sharing

- Ensure privacy considerations are addressed
- Document browser compatibility requirements
- Consider performance impact on different devices


### Voice Interaction

- Include clear audio processing documentation
- Test with different accents and voice patterns
- Consider accessibility requirements


### Gemini API Integration

- Clearly document API usage and rate limits
- Handle API errors gracefully
- Include fallback mechanisms for when API is unavailable


## Documentation Standards

- **Code Comments**: Document complex logic and the "why" behind implementation choices
- **API Documentation**: Include input/output formats and error scenarios
- **User Documentation**: Update user guides when adding new features
- **Architectural Decisions**: Document significant design choices in ADR format[^5]


## Communication Channels

- **GitHub Issues**: For bug reports and feature discussions
- **Pull Requests**: For code reviews and implementation details
- **Discord Channel**: For real-time discussion (link in README)


## Issue Reporting

When reporting bugs, include:

- Steps to reproduce
- Expected vs. actual behavior
- Browser/OS environment
- Console logs or error messages
- Screenshots or recordings where applicable[^7]


## Recognition Model

All contributors will be acknowledged in our README.md and CONTRIBUTORS.md files. Significant contributions may result in maintainer status.

## Code of Conduct

We follow the Contributor Covenant Code of Conduct. Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before participating. We expect all contributors to be respectful, considerate, and constructive in all interactions.

---

Remember, the best contributions start small. Don't hesitate to ask questions if you're unsure about any aspect of the contribution process[^2][^3]. We're excited to have you join our community!

<div style="text-align: center">⁂</div>

[^1]: https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/5653834/babca5a8-c26e-4f32-97e5-20e12bbe9543/paste-1.txt

[^2]: https://www.reddit.com/r/learnmachinelearning/comments/92x06o/how_can_i_significantly_contribute_to_open_source/

[^3]: https://www.reddit.com/r/github/comments/1jsply8/contributing_to_opensource_project/

[^4]: https://www.reddit.com/r/ExperiencedDevs/comments/16dwrbq/how_to_set_standards_for_an_entire_team_of_devs/

[^5]: https://www.restack.io/p/github-resources-multimodal-ai-answer

[^6]: https://www.reddit.com/r/ChatGPTCoding/comments/1jj0q2p/i_completed_a_project_with_100_aigenerated_code/

[^7]: https://www.digitalocean.com/resources/articles/how-to-contribute-to-open-source

[^8]: https://www.realityai.tech/open-source-help-center-articles/understanding-contribution-guidelines

[^9]: https://www.daytona.io/dotfiles/10-best-practices-for-contributing-to-open-source-projects

[^10]: https://www.leanware.co/insights/best-practices-ai-software-development

[^11]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11800295/

[^12]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7745495/

[^13]: https://www.semanticscholar.org/paper/670e2331f78028f14ccfc94399eba72eccd53642

[^14]: https://www.semanticscholar.org/paper/53b39326e583bb2d44a0a43c9d647a4516de2c27

[^15]: https://www.reddit.com/r/learnprogramming/comments/140gdp8/a_stepbystep_for_doing_your_first_open_source/

[^16]: https://www.reddit.com/r/opensource/comments/1d4ou76/how_should_i_start_contributing_open_source/

[^17]: https://www.reddit.com/r/opensource/comments/1bwbsa8/i_want_to_contribute_to_open_source_projects/

[^18]: https://www.reddit.com/r/opensource/comments/qpcslx/contributing_to_documentation_in_opensource/

[^19]: https://www.reddit.com/r/FlutterDev/comments/1ewumxq/can_i_start_contributing_to_github_as_a_beginner/

[^20]: https://www.reddit.com/r/ClaudeAI/comments/1egxxmz/not_enough_people_are_getting_creative_with/

[^21]: https://www.reddit.com/r/csharp/comments/1bxprbo/how_do_people_do_open_source_contributions/

[^22]: https://www.reddit.com/r/ChatGPTCoding/comments/1f51y8s/a_collection_of_prompts_for_generating_high/

[^23]: https://www.reddit.com/r/AskProgramming/comments/13xr918/tips_and_guidelines_for_contributing_to_open/

[^24]: https://www.reddit.com/r/ClaudeAI/comments/1enle9c/can_someone_explain_how_to_actually_use_claude/

[^25]: https://www.reddit.com/r/LocalLLaMA/comments/1k9bdlh/lack_of_model_compatibility_can_kill_promising/

[^26]: https://www.reddit.com/r/softwaredevelopment/comments/lt226k/how_do_you_organize_your_software_development/

[^27]: https://www.reddit.com/r/ChatGPTCoding/comments/1hvuqyn/ask_chatgptcoding_what_are_your_aiassisted_coding/

[^28]: https://www.reddit.com/r/opensource/comments/xkt9hc/what_are_some_interesting_open_source_projects_to/

[^29]: https://www.reddit.com/r/learnmachinelearning/comments/18iecqw/seeking_advice_on_efficiently_contributing_to_the/

[^30]: https://docs.evolveum.com/community/development/code-contribution-guidelines/

[^31]: https://www.codegrade.com/blog/how-to-configure-an-ai-assistant-for-code

[^32]: https://www.restack.io/p/starting-an-open-source-ai-project-answer-best-practices-cat-ai

[^33]: https://pieces.app/blog/how-to-contribute-to-open-source-the-ultimate-guide

[^34]: https://docs.github.com/articles/setting-guidelines-for-repository-contributors

[^35]: https://graphite.dev/guides/best-practices-open-source-project-contributions

[^36]: https://www.reddit.com/r/ChatGPTCoding/comments/1h68j1n/what_i_learned_in_the_last_4_weeks_using_ai/

[^37]: https://blog.codacy.com/best-practices-for-coding-with-ai

[^38]: https://dev.to/hexadecimalsoftware/get-involved-a-step-by-step-guide-to-open-source-contributions-kjd

[^39]: http://mozillascience.github.io/working-open-workshop/contributing/

[^40]: https://www.opslevel.com/resources/standards-in-software-development-and-9-best-practices

[^41]: https://dev.to/giteden/ai-coding-assistants-starter-templates-and-more-a-guide-to-working-less-f0a

[^42]: https://contribute.cncf.io/contributors/getting-started/

[^43]: https://www.semanticscholar.org/paper/b5a0241df6073c406e8539215eb94a07e8833296

[^44]: https://www.semanticscholar.org/paper/1ab2aee96abad5b45fd21f60ae57cea6c3f62751

[^45]: https://www.semanticscholar.org/paper/aedde38b00937872f5957b86a1e78933b5fe08fc

[^46]: https://www.semanticscholar.org/paper/bc830cd622d6b46f11d5047c19aa26e339d05bd2

[^47]: https://www.semanticscholar.org/paper/235aaa89ccb8901b1a8b4b88e65cce6b2766ef93

[^48]: https://www.semanticscholar.org/paper/bc9fe1c6cbaf666514581aed2090ab9ab84c9f76

[^49]: https://www.reddit.com/r/outlier_ai/comments/1dmcht5/i_am_an_outlier_manager_and_this_is_what_you_need/

[^50]: https://www.reddit.com/r/ChatGPTCoding/comments/1gznijl/how_to_code_aipowered_apps_effectively/

[^51]: https://discuss.scientific-python.org/t/a-policy-on-generative-ai-assisted-contributions/1702

