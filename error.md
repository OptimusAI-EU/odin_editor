ain 2025-07-13T03:41:15.661Z] [CSS_DEV] DONE, 267 css modules (167ms)
[main 2025-07-13T03:41:15.795Z] TypeError: undefined is not iterable (cannot read property Symbol(Symbol.iterator))
    at ThemeMainService.getWindowSplash (file:///C:/code/void/out/vs/platform/theme/electron-main/themeMainService.js:211:59)
    at CodeWindow.updateConfiguration (file:///C:/code/void/out/vs/platform/windows/electron-main/windowImpl.js:860:59)
    at CodeWindow.load (file:///C:/code/void/out/vs/platform/windows/electron-main/windowImpl.js:787:14)
    at WindowsMainService.doOpenInBrowserWindow (file:///C:/code/void/out/vs/platform/windows/electron-main/windowsMainService.js:1271:16)
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async WindowsMainService.openInBrowserWindow (file:///C:/code/void/out/vs/platform/windows/electron-main/windowsMainService.js:1226:13)
    at async WindowsMainService.doOpen (file:///C:/code/void/out/vs/platform/windows/electron-main/windowsMainService.js:425:31)
    at async WindowsMainService.open (file:///C:/code/void/out/vs/platform/windows/electron-main/windowsMainService.js:225:63)
    at async CodeApplication.startup (file:///C:/code/void/out/vs/code/electron-main/app.js:512:9)
    at async CodeMain.startup (file:///C:/code/void/out/vs/code/electron-main/main.js:103:13)
[34892:0713/104115.963:ERROR:command_buffer_proxy_impl.cc(331)] GPU state invalid after WaitForGetOffsetInRange.
[34892:0713/104115.992:ERROR:command_buffer_proxy_impl.cc(331)] GPU state invalid after WaitForGetOffsetInRange.
