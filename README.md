# LifeCycle

Change SceneDelegate to AppDelegate project:
* remove SceneDelegate.swift
* Info.plist: remove Application Scene Manifest
* AppDelegate.swift: add property `var window: UIWindow?`
* AppDelegate.swift: remove section below `// MARK: UISceneSession Lifecycle`
