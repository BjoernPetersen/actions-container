## v3.7.4 (2024-10-06)

### Fix

- **deps**: update dependency pre-commit to v4

## v3.7.3 (2024-08-29)

### Fix

- **deps**: update gcr.io/kaniko-project/executor docker tag to v1.23.2

## v3.7.2 (2024-06-30)

### Fix

- Correctly authenticate for private source contexts

## v3.7.1 (2024-06-28)

### Fix

- **build-image-kaniko**: Remove unwanted quotes from APP_VERSION build arg

## v3.7.0 (2024-06-23)

### Feat

- **deps**: update artifact actions to v4

## v3.6.0 (2024-06-23)

### Feat

- Add option to generate Docker build summary

## v3.5.1 (2024-06-08)

### Fix

- **deps**: update gcr.io/kaniko-project/executor docker tag to v1.23.1

## v3.5.0 (2024-05-26)

### Feat

- Add timeout-minutes input

## v3.4.0 (2024-05-26)

### Feat

- Bump version on kaniko updates

## v3.3.0 (2024-03-21)

### Feat

- Add containerfile param to build actions

## v3.2.0 (2023-11-18)

### Feat

- Add image name and tag as outputs

## v3.1.0 (2023-11-12)

### Feat

- Add build workflow using kaniko

## v3.0.4 (2023-11-12)

### Fix

- **build-image-docker**: Check out repo if git context is not used

## v3.0.3 (2023-11-11)

### Fix

- Don't require platform input

## v3.0.2 (2023-11-11)

### Fix

- Only set up QEMU for targeted platform

## v3.0.1 (2023-11-11)

### Fix

- Build image with correct platform if non-amd64 is set

## v3.0.0 (2023-11-11)

### BREAKING CHANGE

- If you relied on the provenance metadata manifest,
this will break your build, because it disables the creation of that.

### Feat

- Add workflow to join multiple images into one
- Add option to store digests as artifact
- Provide image digest as build output
- Add possiblity to specify platform for build-image-docker

## v2.6.0 (2023-11-06)

### Feat

- Add input to specify additional build args
- Add input for target stage

## v2.5.1 (2023-10-21)

### Fix

- Respect image-name input in clean job

## v2.5.0 (2023-10-21)

### Feat

- Allow setting a custom version

### Fix

- Set up buildx in docker build job

## v2.4.0 (2023-10-21)

### Feat

- Allow setting a custom build context

## v2.3.2 (2023-10-21)

### Fix

- Remove typo in build tags expression

## v2.3.1 (2023-10-21)

### Fix

- Try using single quotes around tags

## v2.3.0 (2023-10-21)

### Feat

- Add continue-on-error input for clean action

## v2.2.0 (2023-10-21)

### Feat

- Introduce clean action

## v2.1.0 (2023-10-21)

### Feat

- Accept image-name input for build-image-docker

## v2.0.0 (2023-10-21)

### BREAKING CHANGE

- You'll need to adjust your branch protection rules
if you depend on the status check name.

### Refactor

- Shorten build-container-image to build

## v1.0.1 (2023-10-21)

### Fix

- Remove condition for build-container-image job

## v1.0.0 (2023-10-21)

Initial version.
