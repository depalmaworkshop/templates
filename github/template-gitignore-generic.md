<!-- 
TEMPLATE: .gitignore - Generic
VERSION: 1.0.0
UPDATED: 2025-08-15
AUTHOR: DePalma Workwear Limited

INSTRUCTIONS:
1. Save as ".gitignore" in repository root
2. Remove sections that don't apply to your project
3. Add project-specific exclusions at the bottom
4. Remove these HTML comments before committing
-->

# ============================================
# Operating System Files
# ============================================

# macOS
.DS_Store
.AppleDouble
.LSOverride
._*

# Windows
Thumbs.db
ehthumbs.db
Desktop.ini

# Linux
*~
.directory
.Trash-*

# ============================================
# IDE and Editor Files
# ============================================

# Visual Studio Code
.vscode/
*.code-workspace

# IntelliJ IDEA
.idea/
*.iml
*.ipr
*.iws

# Sublime Text
*.sublime-project
*.sublime-workspace

# Vim
*.swp
*.swo
*.swn
.*.swp

# Obsidian
.obsidian/

# ============================================
# Environment and Configuration
# ============================================

# Environment variables
.env
.env.*
!.env.example
!.env.template

# API keys and secrets
.keys
*.pem
*.key
*.cert

# ============================================
# Dependencies and Package Management
# ============================================

# Node.js
node_modules/
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*

# Python
__pycache__/
*.py[cod]
*$py.class
venv/
env/
.Python

# ============================================
# Build Outputs and Artifacts
# ============================================

# Common build directories
dist/
build/
out/
target/
*.build/

# Compiled files
*.com
*.class
*.dll
*.exe
*.o
*.so

# ============================================
# Logs and Temporary Files
# ============================================

# Log files
*.log
logs/
*.log.*

# Temporary files
tmp/
temp/
*.tmp
*.bak
*.backup
*.cache

# ============================================
# Project-Specific Exclusions
# ============================================

# [ADD YOUR PROJECT-SPECIFIC EXCLUSIONS HERE]
# Example:
# _Supabase Objects - */
# public/uploads/
# data/*.csv