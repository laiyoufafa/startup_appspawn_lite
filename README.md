# appspawn\_lite<a name="EN-US_TOPIC_0000001081995748"></a>

-   [Introduction](#section469617221261)
-   [Directory Structure](#section15884114210197)
-   [Constraints](#section12212842173518)
-   [Repositories Involved](#section641143415335)

## Introduction<a name="section469617221261"></a>

The appspawn\_lite module spawns application processes upon receiving commands from the application framework, configures permissions for new processes, and calls the entry function of the application framework.

## Directory Structure<a name="section15884114210197"></a>

```
base/startup/appspawn_lite/     # appspawn_lite module
├── LICENSE
└── services
    ├── include              # Header files for the appspawn_lite module
    ├── src                  # Source files for the appspawn_lite module
    └── test                 # Source files of the test cases for the appspawn_lite module
        └── unittest
```

## Constraints<a name="section12212842173518"></a>

Currently, the appspawn\_lite module applies only to small-system devices \(reference memory ≥ 1 MB\), for example, Hi3516D V300 and Hi3518E V300.

## Repositories Involved<a name="section641143415335"></a>

Startup subsystem

hmf/startup/syspara\_lite

**hmf/startup/appspawn\_lite**

hmf/startup/bootstrap\_lite

hmf/startup/init\_lite

