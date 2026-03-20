# Contributing to GameRebellion

Thank you for your interest in contributing. These guidelines apply to all public repositories under the [GameRebellion](https://github.com/gamerebellion) organization.

## Reporting Bugs

Open a [GitHub Issue](https://github.com/gamerebellion/gamerebellion-unity-sdk/issues) on the relevant repository. Include:

- SDK version and engine version (e.g. Unity 2022.3, `com.gamerebellion.sdk` v0.1.0)
- Target platform (iOS, Android, Editor)
- Steps to reproduce
- Expected vs. actual behavior
- Relevant logs (enable `GRLogDrainer` for SDK-level logs)

## Submitting Changes

1. **Fork** the repository
2. **Branch** from `main` using a descriptive name:
   - `feat/add-webgl-support`
   - `fix/session-stop-not-firing`
   - `docs/update-integration-guide`
3. **Make your changes** — match the existing code style and patterns
4. **Test** your changes on at least one target platform
5. **Commit** with a clear message following [Conventional Commits](https://www.conventionalcommits.org/):
   ```
   feat(unity): add WebGL transport adapter
   fix(batcher): flush events on application pause
   docs: update Quick Start for UPM installation
   ```
6. **Open a Pull Request** against `main` with a description of what changed and why

## Code Style

- Match existing patterns in the repository
- C# (Unity SDK): follow Microsoft C# conventions, use `#region` sparingly
- Python (backend): PEP 8, type hints required
- TypeScript (web): strict mode, no `any` types

## Architecture Context

For a high-level understanding of how the SDK, API, and platform fit together, see the architecture diagram in the [organization README](https://github.com/gamerebellion) or the full documentation at [docs.gamerebellion.com](https://docs.gamerebellion.com).

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
