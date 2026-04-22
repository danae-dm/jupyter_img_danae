// build singularity image
buildSingularityImage([
    recipeFile: 'my-recipe.def',
    imageName: 'jupyter-danae',
    pushRegistry: 'singularity.vbc.ac.at',
    pushRegistryNamespace: 'demo', // i.e. singularity hub collection
    pushRegistryCredentials: 'demo-creds-singularity',
    pushBranches: ['develop', 'master', 'my_feature']
])