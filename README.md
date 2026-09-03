# paperops-agent-pause

Fill in the knowledge gap in paperops-agent



因通过 Vibe-coding 构建了 paperops-agent ，但因本身技术不到位，产生了知识差距。该仓库旨在尝试运用边学边实践的方式，逐步将知识降级，快速了解与吸收。



查看git记录发现Vibe Coding主要分为两个阶段:

20260714 \~ 20260727 

&#x20;   Claude Code 验证基于Langgraph实现Agent原型系统是否成立

&#x20;   (Claude Code 接入的是deepseek v4 pro)

20260807 \~ 20260902 

&#x20;   CodeX 验证基于Langraph实现的Agent系统相比Rag系统是否能够提高效率

&#x20;   (CodeX 接入的是GPT 5.6 sol)



查看git commit记录发现在Claude阶段存在命名不规范问题

&#x09;于是学习一下git commit命名规范:

&#x09;feat:       feature新加功能     Minor++

&#x09;fix:          修复bug                  Patch ++

&#x09;docs:      修改文档

&#x09;style:      不改变代码功能，改变风格样式的

&#x09;chore:     杂活，写配置要求的，如CI配置要求，环境依赖包

&#x09;refactor:  功能不变，代码重构

&#x09;perf:        性能优化

&#x09;test:         测试文件

&#x20;   feat!:        带有破坏性质的修改，不向低版本兼容

&#x20;   软件版本格式: Major.Minor.Patch

