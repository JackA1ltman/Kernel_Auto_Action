# Kernel Auto Action
Automate the compilation of the Android Kernel using GitHub Actions, with optional inclusion of KSU and SUSFS. Thanks to xiaoleGun's project KernelSU_Action for providing ideas and inspiration~⭐.
# File Tree
  - .github
    - .workflows
      - build_with_ksu.yaml
      - build_with_nonroot.yaml
      - build_with_ksu_with_susfs.yaml
  - config.env
  - README.MD
# Enviroment
  - CONFIG_
    - MODE
      - 0 for Non-Root mode, 1 for KSU mode, 2 for KSU with SUSFS mode
    - 
  - KernelSU
    - GIT_SOURCE and GIT_BRANCH
      - Enter the GitHub address of the KSU project and its branch. Since there are many branches of KSU, you can choose the main or a specific branch of the KSU project based on your needs. The default is the main KSU project.
      - 
