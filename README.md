# github-actions
Repository for testing GitHub Actions

## Features
- CI/CD Automation
- Code & Repository Management

## Structure
```sh
repository
├── worflow1
│   ├── job1
│   │   ├── step1
│   │   └── step2
│   └── job2
│       └── step1
├── worflow2
│   └── job1
│       ├── step1
│       ├── step2
│       ├── step3
│       └── step4
└── worflow3
    ├── job1
    │   └── step1
    └── job2
        └── step1
```

## Key Components
### Workflows
- Attached to a `GitHub repository`
- Contain one or more `Jobs`
- Triggered upon `Events`

### Jobs
- Define a `Runner` (execution environment)
- Contain one or more `Steps`
- Can run in parallel(default) or sequential
- Can be conditional

### Steps
- Execute a `shell script` or an `Action`
- Can use custom or third-party actions
- Are executed in order
- Can be conditional

## References
- [academind/github-actions-course-resources](https://github.com/academind/github-actions-course-resources)
