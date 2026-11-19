# Repository policy for Codex

- `PetcuDavid/openshorts` is the maintained repository for the private content factory. Set it as `origin`; keep `mutonby/openshorts` as an optional, read-only `upstream` source for reviewed updates.
- Do not open pull requests, push branches, or submit fixes to upstream repositories without the user's explicit authorization. Make local OpenShorts changes in our fork.
- Preserve the local Gemini model configuration, `.env`, original recordings, generated outputs, and Docker volumes. Do not expose credentials in logs or commits.
- Do not start live Gemini jobs, upload media, create review Issues, or publish content unless the current task explicitly authorizes those actions.
- Keep the renderer's Remotion packages aligned with the composition's locked version. Validate bundle startup, health, and a local renderer-only fixture before changing rendering dependencies.
