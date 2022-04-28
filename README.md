# GithubRepoGenerator
 - runs in the git repository containing some documenation files
 - extracts from it the terms that look like names of programs
 - chooses a template for the project based of text of `README.md`, scaffolds it
   - *leverages cmake?*
   - Picks a template from a folder of templates
     - SwiftUI iOS app
     - RealityKit iOS app
     - Unity iOS AR project
     - Unreal iOS AR project
     - python package
     - ReactJS one page static app
     - Etherium Smart Contract
     - autotools C++ project
 - populates it with code generated with prompts extracted from `Usage` and `UI` parts of `README.md`

Uses OpenAI Codex or alternative 
