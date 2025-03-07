# Docs Template

Folder docs:  
- Template files to set new project repo with docs folder.
- It has structure

```plaintext
docs/
└── log/
    └── 2025/
        ├── task/
        │   └── 03.md
        └── time/
            ├── 03_in.json
			├── add_day.py
			├── calculate_month_time.py
			└── generate_month_file.py
```

- This is used to track project tasks and time.
- Scripts are 'in place' to handle time calculations.
- Scripts could be centralized in new repo and load to projects with pip package.  
  For now i dont see worth it to spend hour to do it.  
  In addition these scripts operate on files in time folder.  
  Centralizing them would break that.  
  Even if centralized, it still would need some script, to run them from each project.
