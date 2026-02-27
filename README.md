# Contributing to Arcbase

First off, thank you for considering contributing to Arcbase! Arcbase is a community-driven project focused on building streamlined, performance-oriented Windows optimization tools. Your contributions help improve reliability, transparency, and user control.

This guide applies to all repositories under the Arcbase organization, including ArcOS and related tooling.

## Code of Conduct

By participating in this project, you agree to maintain a respectful, constructive, and inclusive environment. Collaboration should remain professional and focused on improving the project.

## How Can I Contribute?

### Bug Reports

If you find a bug:

1. Search existing issues first.
2. If it’s new, open an issue including:
   - A clear title
   - Steps to reproduce
   - Expected vs actual behavior
   - Windows version/build
   - ArcOS version

Be specific. Clear reports help us resolve issues faster.

### Security Concerns

Do not report security-related concerns via public issues.

Instead, contact:

security@arcbase.one

(Replace with your actual contact email before publishing.)

### Feature Requests

Before submitting a feature request:

- Check if it has already been proposed.
- Explain the problem it solves.
- Describe the expected behavior.
- Consider compatibility with Windows 10 and 11.

Arcbase prioritizes:
- Stability
- Reversibility
- Update compatibility
- Clean system modification practices

### Documentation Contributions

Clear documentation is critical for system-level tools.

You can help by:

- Improving README clarity
- Adding usage examples
- Expanding troubleshooting sections
- Writing rollback guidance
- Translating documentation

### Code Contributions

1. Find an Issue  
   Look for `good first issue` or `help wanted`.

2. Fork & Clone  
   Fork the repository and clone it locally.

3. Create a Branch  
   Use descriptive naming, for example:
   - feature/ui-optimization
   - fix/service-detection
   - improvement/uninstall-logic

4. Follow Project Structure  
   - Keep modules modular.
   - Respect config-based toggles.
   - Avoid hardcoding values where possible.

5. Test in a VM  
   Never submit changes without testing in:
   - A clean Windows 10 or 11 VM
   - After reboot
   - After Windows Update check

6. Open a Pull Request  
   Include:
   - A clear summary
   - Windows build tested on
   - Before/after behavior
   - Screenshots (if UI-related)

## Development Ecosystem

Arcbase primarily uses:

- PowerShell — system configuration and automation
- Batch scripts — launchers and privilege elevation
- JSON — configuration control
- Git — version control

Future tooling may include:

- Installer packaging
- GUI frontend (WPF / WinUI)
- Automated test validation in virtual environments

## Style & Quality Standards

- Keep scripts modular and readable.
- Avoid unsafe system modifications.
- Do not remove servicing stack components.
- Always provide uninstall or rollback paths.
- Prefer policy-based configuration over binary tampering.

Arcbase prioritizes long-term system stability over aggressive stripping.

## Release Guidelines

Before submitting features that:

- Modify services
- Change system policies
- Adjust system behavior

You must test:

- Reboot stability
- Windows Update functionality
- Defender integrity
- Driver installation
- New user account behavior

## Community

Project resources:

GitHub: https://github.com/arcbase  
Contact: hello@arcbase.one  

(Replace URLs and emails before publishing.)

Thank you for contributing to Arcbase.
