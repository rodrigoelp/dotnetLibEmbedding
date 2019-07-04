# Embedding dotnet libraries in a native iOS app.

The whole reason to do this project is to investigate how to get a dotnet library in an iOS app following [this guide](https://docs.microsoft.com/en-us/xamarin/tools/dotnet-embedding/get-started/objective-c/ios)

## To run the embedding process

1. Compile the project to generate the dll.
2. Run in terminal `sh framework-gen.sh`. This should generate a framework file located in the `output` directory.

