# Dataset Acquisition and Storage

## Source
- Official repository: `https://github.com/zae-bayern/elpv-dataset.git`
- Pinned commit: `93e82ae507c36b3f2c8227eade8b792fcbefcca6`
- Images: CC BY-NC-SA 4.0; code: Apache-2.0 as stated by the source repository.
- Primary task retains defect-probability 0.0 as Functional and 1.0 as Defective; 401 intermediate-probability images are excluded from the primary binary endpoint.

## Storage design
Raw images are not redistributed in this repository. Clone the pinned source into `data/raw/elpv-dataset/` locally. That path is excluded by `.gitignore`. Derived split/audit tables and model evidence are versioned under `artifacts/`.
