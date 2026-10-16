// build singularity image
buildSingularityImage([
    imageName: 'jupyter-danae',
    recipeFile: 'Singularity.def',

    pushRegistry: 'singularity.vbc.ac.at',
    pushRegistryNamespace: 'demo',
    pushRegistryCredentials: 'demo-creds-singularity',

    pushBranches: ['main'],
    runTest: true,
])
