# AI Team Java

Java-stack specialization layer for the shared AI-team operating model.

## Intended Contents

- Java role overlays (Spring Boot / Maven / Gradle profiles)
- Java security/testing/build conventions
- Java-specific skill packs and checklists

## Suggested Layout

```text
ai-team-java/
  profiles/
  skills/
  templates/
  policies/
  scripts/
```

## Integration

Use with `ai-team-core` as follows:

1. Keep orchestration and scoring in `ai-team-core`.
2. Load Java profile/skills from this repo per task.
3. Track stack-specific improvements here.

