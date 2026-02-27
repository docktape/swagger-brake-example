# swagger-brake-example

Example project demonstrating how to integrate swagger-brake into both Maven and Gradle builds. Uses a local Artifactory instance to simulate publishing and consuming API specs.

## Tech Stack

- Build: Maven (Maven example), Gradle (Gradle example)
- Infrastructure: Artifactory (local Docker instance for artifact resolution)

## Project Structure

- `swagger-brake-maven-example/` - Maven project showing swagger-brake Maven plugin integration
- `swagger-brake-gradle-example/` - Gradle project showing swagger-brake Gradle plugin integration

## Key Notes

- These are example/demo projects, not production code — do not modify for feature development
- A local Artifactory server must be running for the examples to resolve the swagger-brake plugin artifacts
- Intended to be kept in sync with the plugin versions in `swagger-brake-maven-plugin` and `swagger-brake-gradle`
