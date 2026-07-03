# Package System Document

## Goals

- Build packages from source
- Keep build simple
- Allow custom flags
- Suport patchs
- Track installed files
- Make the base system reproducible

## Initial Idea

Each package has a build script recipe

packages/
└── bash/
    └── build.sh

This first version does not need to be a real package manager It only needs to build and install packages in the correct order.
