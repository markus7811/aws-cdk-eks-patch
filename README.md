# aws-cdk-eks-patch
This [patch-package](https://www.npmjs.com/package/patch-package) patch fixes the cdk [issue](https://github.com/aws/aws-cdk/issues/11543). At the moment the cdk cli won't recognize aws eks web identity credential settings.

# How 2 use:

1. place the patch folder in your project directory
3. add [patch-package](https://www.npmjs.com/package/patch-package) to your package.json
4. add ```"postinstall": "patch-package"``` to your package.json scripts
5. Enjoy the cdk-cli on eks runtimes
