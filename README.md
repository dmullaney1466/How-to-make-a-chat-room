[ {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "2b370c56-b256-433e-b70a-3ce99cb3d158",
   "id": "ahfgeienlihckogmohjhadlkjgocpleb",
   "location": "COMPONENT",
   "manifest_version": 1,
   "name": "Web Store",
   "path": "/opt/google/chrome/resources/web_store",
   "permissions": {
      "active": {
         "api": [ "management", "system.display", "system.storage", "webstorePrivate", "system.cpu", "system.memory", "system.network" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_HOSTED_APP",
   "version": "0.2"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 10,
      "listeners": [ {
         "event_name": "alarms.onAlarm",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "alarms.onAlarm",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "tabs.onRemoved",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "tabs.onRemoved",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "tabs.onUpdated",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "tabs.onUpdated",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "webRequest.onBeforeRequest/s1",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "webRequest.onBeforeRequest/s2",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "webRequest.onBeforeRequest/s3",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      }, {
         "event_name": "webRequest.onBeforeRequest/s4",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bdihlblbmmgdnpdadmgkmmnknecngknc/"
      } ]
   },
   "guid": "2dbd8529-4962-4986-9e74-d7609605eabb",
   "id": "bdihlblbmmgdnpdadmgkmmnknecngknc",
   "location": "EXTERNAL_POLICY_DOWNLOAD",
   "manifest_version": 3,
   "name": "Managed Methods",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/bdihlblbmmgdnpdadmgkmmnknecngknc/3.6.5_0",
   "permissions": {
      "active": {
         "api": [ "alarms", "desktopCapture", "downloads", "geolocation", "identity", "identity.email", "notifications", "storage", "tabs", "webRequest", "enterprise.deviceAttributes", "enterprise.networkingAttributes", "scripting", "declarativeNetRequestWithHostAccess", "offscreen" ],
         "explicit_hosts": [ "*://*/*", "\u003Call_urls>" ],
         "manifest": [  ],
         "scriptable_hosts": [ "*://127.0.0.1/*", "*://cfconsole.managedmethodsdev.com/control-extension", "*://cfdev.managedmethodsdev.com/control-extension", "*://content-filter-custom-block-page-k6wbttzueq-uc.a.run.app/browser-locked", "*://content-filter-custom-block-page-l6vq7eiebq-uc.a.run.app/browser-locked", "*://localhost/*", "\u003Call_urls>" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [ {
         "extra_data": "266268BE6C76EA4CF0D0B2813EADFC20:17",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "266268BE6C76EA4CF0D0B2813EADFC20:17",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      } ],
      "count": 2
   },
   "type": "TYPE_EXTENSION",
   "version": "3.6.5"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 2,
      "listeners": [ {
         "event_name": "app.runtime.onLaunched",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "app.runtime.onRestarted",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      } ]
   },
   "guid": "9385732c-ca50-4b07-8828-74ce92f17062",
   "id": "bkkfbdphgelkfacndikjegbhnljnilhf",
   "location": "EXTERNAL_POLICY_DOWNLOAD",
   "manifest_version": 2,
   "name": "Schoolnet Secure Tester",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/bkkfbdphgelkfacndikjegbhnljnilhf/1.0.30_1",
   "permissions": {
      "active": {
         "api": [ "app.window.alwaysOnTop", "fileSystem", "fileSystem.directory", "fileSystem.retainEntries", "app.window.fullscreen", "app.window.fullscreen.overrideEsc", "power", "storage", "system.display", "webview", "system.network" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [ "audioCapture" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_PLATFORM_APP",
   "version": "1.0.30"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 2,
      "listeners": [ {
         "event_name": "runtime.onConnectExternal",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bpmcpldpdmajfigpchkicefoigmkfalc/"
      }, {
         "event_name": "tabs.onRemoved",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://bpmcpldpdmajfigpchkicefoigmkfalc/"
      } ]
   },
   "guid": "00f3d2ec-11c5-4fcc-91a2-5f4ef16e734f",
   "id": "bpmcpldpdmajfigpchkicefoigmkfalc",
   "location": "COMPONENT",
   "manifest_version": 3,
   "name": "Basic Editor for Office files",
   "path": "/usr/share/chromeos-assets/quickoffice",
   "permissions": {
      "active": {
         "api": [ "clipboardRead", "clipboardWrite", "cookies", "downloads", "fileSystem", "fileSystem.write", "identity", "identity.email", "metricsPrivate", "storage", "unlimitedStorage" ],
         "explicit_hosts": [ "*://*.google.com/*", "https://www.google-analytics.com/*", "https://www.googleapis.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "152.160.162"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 10,
      "listeners": [ {
         "event_name": "alarms.onAlarm",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "alarms.onAlarm",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "cookies.onChanged",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "cookies.onChanged",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "identity.onSignInChanged",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "identity.onSignInChanged",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "idle.onStateChanged",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "idle.onStateChanged",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://callobklhcbilhphinckomhgkigmfocg/"
      } ]
   },
   "guid": "ee45aea6-28cf-4dd3-815d-e8db1a9c6d90",
   "id": "callobklhcbilhphinckomhgkigmfocg",
   "location": "EXTERNAL_POLICY_DOWNLOAD",
   "manifest_version": 3,
   "name": "Endpoint Verification",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/callobklhcbilhphinckomhgkigmfocg/1.134.0_0",
   "permissions": {
      "active": {
         "api": [ "alarms", "cookies", "enterprise.platformKeys", "gcm", "identity", "identity.email", "idle", "nativeMessaging", "platformKeys", "storage", "enterprise.deviceAttributes", "enterprise.reportingPrivate", "offscreen" ],
         "explicit_hosts": [ "*://*.google.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.134.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [ "DISABLE_UNSUPPORTED_MANIFEST_VERSION" ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "93e0040f-66d3-413a-93ed-b7680a428ffe",
   "id": "cgbbbjmgdpnifijconhamggjehlamcif",
   "location": "EXTERNAL_POLICY_DOWNLOAD",
   "manifest_version": 2,
   "name": "Gopher Buddy",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/cgbbbjmgdpnifijconhamggjehlamcif/0.9.9.3_1",
   "permissions": {
      "active": {
         "api": [ "alarms", "browsingData", "identity", "identity.email", "idle", "notifications", "storage", "enterprise.deviceAttributes" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [ "https://gopher-buddy-dev.appspot.com/*", "https://gopher-buddy-prod.appspot.com/*" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "0.9.9.3"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 1,
      "listeners": [ {
         "event_name": "app.runtime.onLaunched",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      } ]
   },
   "guid": "a650640a-2fcf-4a39-9984-a6dfd0d88908",
   "id": "cnbgggchhmkkdmeppjobngjoejnihlei",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Play Store",
   "path": "/opt/google/chrome/resources/chromeos/arc_support",
   "permissions": {
      "active": {
         "api": [ "browser", "nativeMessaging", "webview" ],
         "explicit_hosts": [ "chrome://resources/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_PLATFORM_APP",
   "version": "0.2.0.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 4,
      "listeners": [ {
         "event_name": "ttsEngine.onPause",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onResume",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onSpeakWithAudioStream",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onStop",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      } ]
   },
   "guid": "c8db19f3-b8f6-45a7-8f14-ce592b26b709",
   "id": "dakbfdmgjiabojdgbiljlhgjbokobjpg",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "eSpeakNG text-to-speech extension",
   "path": "/usr/share/chromeos-assets/speech_synthesis/espeak-ng",
   "permissions": {
      "active": {
         "api": [ "storage", "ttsEngine" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.49.3.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [ "DISABLE_USER_ACTION" ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "54de8c5d-a25e-42c4-b057-b9ab00960ea6",
   "id": "ecnphlgnajanjnkcmbpancdjoidceilk",
   "location": "INTERNAL",
   "manifest_version": 3,
   "name": "Kami for Google Chromeâ„¢",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/ecnphlgnajanjnkcmbpancdjoidceilk/2.0.21404_0",
   "permissions": {
      "active": {
         "api": [ "contextMenus", "printerProvider", "storage", "tabs", "webNavigation", "webRequest", "declarativeNetRequest", "scripting", "offscreen" ],
         "explicit_hosts": [ "\u003Call_urls>" ],
         "manifest": [  ],
         "scriptable_hosts": [ "\u003Call_urls>", "https://*.instructure.com/*/assignments/*", "https://*.instructure.com/*/assignments/*/edit*", "https://*.instructure.com/*/assignments/new*", "https://*.kami.systems/web/*", "https://*.kamihq.com/web/*", "https://*.kamipdf.com/web/*", "https://*.officeapps.live.com/*", "https://*.onedrive.live.com/*", "https://*.sharepoint.com/*p*/r/*", "https://*.sharepoint.com/*w*/r/*", "https://app.peardeck.com/*", "https://assignments.onenote.com/*", "https://classroom.google.com/*", "https://classroom.google.com/*g/tg/*", "https://docs.google.com/*", "https://docs.google.com/document/d/*", "https://docs.google.com/presentation/d/*", "https://docs.google.com/spreadsheets/d/*", "https://drive.google.com/*", "https://drive.google.com/picker*", "https://jamboard.google.com/*", "https://jamboard.google.com/d/*", "https://tealearn.instructure.com/courses/*/pages/*", "https://www.canva.com/design/*", "https://www.teacherspayteachers.com/**" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "2.0.21404"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [ "DISABLE_UNSUPPORTED_MANIFEST_VERSION" ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "4f275451-e407-46c2-a888-4c16086859a8",
   "id": "eebnbmbhdfnfhfhigoklhaklkodghbla",
   "location": "EXTERNAL_POLICY_DOWNLOAD",
   "manifest_version": 2,
   "name": "Destiny Discover",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/eebnbmbhdfnfhfhigoklhaklkodghbla/1.0.8_0",
   "permissions": {
      "active": {
         "api": [ "cookies", "notifications", "storage", "tabs" ],
         "explicit_hosts": [ "http://www.google.ca/*", "http://www.google.co.th/*", "http://www.google.co.ve/*", "http://www.google.com.au/*", "http://www.google.com.co/*", "http://www.google.com.mx/*", "http://www.google.com.ph/*", "http://www.google.com.pr/*", "http://www.google.com.sg/*", "http://www.google.com.vn/*", "http://www.google.com/*", "https://dly-search.follettsoftware.com/*", "https://qat-search.follettsoftware.com/*", "https://search.follettsoftware.com/*", "https://uat-search.follettsoftware.com/*", "https://www.google.ca/*", "https://www.google.co.th/*", "https://www.google.co.ve/*", "https://www.google.com.au/*", "https://www.google.com.co/*", "https://www.google.com.mx/*", "https://www.google.com.ph/*", "https://www.google.com.pr/*", "https://www.google.com.sg/*", "https://www.google.com.vn/*", "https://www.google.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [ "http://www.google.ca/*", "http://www.google.co.th/*", "http://www.google.co.ve/*", "http://www.google.com.au/*", "http://www.google.com.co/*", "http://www.google.com.mx/*", "http://www.google.com.ph/*", "http://www.google.com.pr/*", "http://www.google.com.sg/*", "http://www.google.com.vn/*", "http://www.google.com/*", "https://www.google.ca/*", "https://www.google.co.th/*", "https://www.google.co.ve/*", "https://www.google.com.au/*", "https://www.google.com.co/*", "https://www.google.com.mx/*", "https://www.google.com.ph/*", "https://www.google.com.pr/*", "https://www.google.com.sg/*", "https://www.google.com.vn/*", "https://www.google.com/*" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.0.8"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 21,
      "listeners": [ {
         "event_name": "accessibilityPrivate.onToggleDictation",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAccessibilityEvent",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAccessibilityTreeDestroyed",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAccessibilityTreeSerializationError",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onActionResult",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAllAutomationEventListenersRemoved",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onChildTreeID",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onGetTextLocationResult",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onNodesRemoved",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onTreeChange",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "input.ime.onBlur",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "input.ime.onFocus",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "input.ime.onSurroundingTextChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "settingsPrivate.onPrefsChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "speechRecognitionPrivate.onError",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "speechRecognitionPrivate.onResult",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "speechRecognitionPrivate.onStop",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "types.ChromeSetting.autoclick.onChange",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "types.ChromeSetting.dictation.onChange",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "types.ChromeSetting.dockedMagnifier.onChange",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "types.ChromeSetting.screenMagnifier.onChange",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      } ]
   },
   "guid": "e6f6c421-3fbb-448d-8887-e166872a746f",
   "id": "egfdjlfmgnehecnclamagfafdccgfndp",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Accessibility Common",
   "path": "/opt/google/chrome/resources/chromeos/accessibility",
   "permissions": {
      "active": {
         "api": [ "accessibilityFeatures.modify", "accessibilityFeatures.read", "accessibilityPrivate", "audio", "commandLinePrivate", "input", "inputMethodPrivate", "metricsPrivate", "settingsPrivate", "tabs", "videoCapture", "languageSettingsPrivate", "speechRecognitionPrivate" ],
         "explicit_hosts": [  ],
         "manifest": [ {
            "automation": {
               "desktop": true
            }
         } ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "137.0.7151.137"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE", "WAS_INSTALLED_BY_DEFAULT" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 2,
      "listeners": [ {
         "event_name": "alarms.onAlarm",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://ghbmnnjooekpmoecnnnilnnbdlolhkhi/"
      }, {
         "event_name": "runtime.onConnectExternal",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://ghbmnnjooekpmoecnnnilnnbdlolhkhi/"
      } ]
   },
   "guid": "b7fd9bec-7ca7-4e24-a4b5-2135c6a1b42b",
   "id": "ghbmnnjooekpmoecnnnilnnbdlolhkhi",
   "location": "EXTERNAL_PREF_DOWNLOAD",
   "manifest_version": 3,
   "name": "Google Docs Offline",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/ghbmnnjooekpmoecnnnilnnbdlolhkhi/1.96.1_0",
   "permissions": {
      "active": {
         "api": [ "alarms", "storage", "unlimitedStorage", "offscreen" ],
         "explicit_hosts": [ "https://docs.google.com/*", "https://drive.google.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.96.1"
}, {
   "background_page_keepalives": {
      "activites": [ {
         "extra_data": "",
         "type": "ACCESSIBILITY"
      }, {
         "extra_data": "",
         "type": "ACCESSIBILITY"
      } ],
      "count": 2
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 9,
      "listeners": [ {
         "event_name": "tts.onEvent",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onPause",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onPause",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "ttsEngine.onResume",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onResume",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "ttsEngine.onSpeak",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onSpeak",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "ttsEngine.onStop",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "ttsEngine.onStop",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      } ]
   },
   "guid": "339115b1-43a6-42a5-9a7d-ec7954893f3d",
   "id": "gjjabgpgjpampikjhjpfhneeoapjbjaf",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Chrome OS built-in text-to-speech extension",
   "path": "/usr/share/chromeos-assets/speech_synthesis/patts",
   "permissions": {
      "active": {
         "api": [ "accessibilityPrivate", "metricsPrivate", "tts", "ttsEngine", "unlimitedStorage" ],
         "explicit_hosts": [ "https://*.gvt1.com/*", "https://dl.google.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "29.6"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE", "WAS_INSTALLED_BY_DEFAULT" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 4,
      "listeners": [ {
         "event_name": "runtime.onStartup",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://gndmhdcefbhlchkhipcnnbkcmicncehk/"
      }, {
         "event_name": "tabs.onRemoved",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://gndmhdcefbhlchkhipcnnbkcmicncehk/"
      }, {
         "event_name": "windows.onBoundsChanged",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://gndmhdcefbhlchkhipcnnbkcmicncehk/"
      }, {
         "event_name": "windows.onFocusChanged",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://gndmhdcefbhlchkhipcnnbkcmicncehk/"
      } ]
   },
   "guid": "1e6bf7df-0d6b-429d-81a3-fdfa9d94fffe",
   "id": "gndmhdcefbhlchkhipcnnbkcmicncehk",
   "location": "EXTERNAL_COMPONENT",
   "manifest_version": 3,
   "name": "Assessment Assistant",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/gndmhdcefbhlchkhipcnnbkcmicncehk/25.530.0_1",
   "permissions": {
      "active": {
         "api": [ "devtools", "enterprise.platformKeys", "management", "storage", "tabs", "webNavigation", "lockWindowFullscreenPrivate" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [ "http://*/*", "https://*/*" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "25.530.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 25,
      "listeners": [ {
         "event_name": "action.onClicked",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "action.onClicked",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "alarms.onAlarm",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "alarms.onAlarm",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "commands.onCommand",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "commands.onCommand",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "contextMenus.onClicked",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "contextMenus.onClicked",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "gcm.onMessage",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "gcm.onMessage",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "runtime.onInstalled",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "runtime.onInstalled",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "runtime.onStartup",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "runtime.onStartup",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "tabs.onActivated",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "tabs.onActivated",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "windows.onFocusChanged",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "windows.onRemoved",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      }, {
         "event_name": "windows.onRemoved",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://inoeonmfapjbbkmdafoankkfajkcphgd/"
      } ]
   },
   "guid": "fd51b1ef-ae84-4bf2-82da-26e69859518d",
   "id": "inoeonmfapjbbkmdafoankkfajkcphgd",
   "location": "INTERNAL",
   "manifest_version": 3,
   "name": "Read&Write for Google Chromeâ„¢",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/inoeonmfapjbbkmdafoankkfajkcphgd/2.1.715_0",
   "permissions": {
      "active": {
         "api": [ "activeTab", "alarms", "contextMenus", "downloads", "gcm", "identity", "identity.email", "management", "storage", "tabs", "search", "scripting", "offscreen" ],
         "explicit_hosts": [ "\u003Call_urls>" ],
         "manifest": [  ],
         "scriptable_hosts": [ "*://docs.google.com/document/*", "*://teams.microsoft.com/*", "\u003Call_urls>", "http://localhost:10901/*", "https://pra.dev.texthelp.com/*", "https://pra.texthelp.com/*", "https://thzbf.texthelp.com/*" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [ {
         "extra_data": "DD6115857E2075BFF97463C6E9D519A0:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:16",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:1",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:10",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B0661A31CB9964766F442F90CFEEB731:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:16",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "DD6115857E2075BFF97463C6E9D519A0:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:1",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:6",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:9",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:13",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:5",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:10",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B1FBA4161DDCC6CDFFBF5B351D220169:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "E50897CA00858304C829E25F52C92102:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:8",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:14",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "E50897CA00858304C829E25F52C92102:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:13",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B9F38D96EB22EDC91DD21369AB2C46C8:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B0661A31CB9964766F442F90CFEEB731:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:3",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:8",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:4",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B1FBA4161DDCC6CDFFBF5B351D220169:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:11",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:15",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:12",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:4",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:9",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B1FBA4161DDCC6CDFFBF5B351D220169:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "5485ACDEE3F47C840FE82CECB594F5B8:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B9F38D96EB22EDC91DD21369AB2C46C8:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "5485ACDEE3F47C840FE82CECB594F5B8:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:7",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:15",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:14",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:5",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "9398F73E30BB7C7353553C6C8697811B:3",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B0661A31CB9964766F442F90CFEEB731:2",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B0661A31CB9964766F442F90CFEEB731:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "1872721F97E367B05879E676DD58C9E8:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "B1FBA4161DDCC6CDFFBF5B351D220169:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:12",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "1872721F97E367B05879E676DD58C9E8:0",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:4",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:6",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:4",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:7",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      }, {
         "extra_data": "FC8CA1C8B92338290DC546E4F6A35DE6:11",
         "timeout_type": "Default",
         "type": "MESSAGE_PORT"
      } ],
      "count": 58
   },
   "type": "TYPE_EXTENSION",
   "version": "2.1.715"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 2,
      "listeners": [ {
         "event_name": "ttsEngine.onSpeakWithAudioStream",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "ttsEngine.onStop",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      } ]
   },
   "guid": "6f7d4147-ed82-4e7c-a3a1-952eebb9cabb",
   "id": "jacnkoglebceckolkoapelihnglgaicd",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Google Enhanced Network text-to-speech extension",
   "path": "/opt/google/chrome/resources/chromeos/accessibility",
   "permissions": {
      "active": {
         "api": [ "ttsEngine" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "137.0.7151.137"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 20,
      "listeners": [ {
         "event_name": "idle.onStateChanged",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "idle.onStateChanged",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onActivated",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onActivated",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onAttached",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onAttached",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onCreated",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onCreated",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onDetached",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onDetached",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onRemoved",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "tabs.onRemoved",
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "webNavigation.onCommitted",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "webNavigation.onCommitted",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "windows.onCreated",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "windows.onCreated",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "windows.onFocusChanged",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "windows.onFocusChanged",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "windows.onRemoved",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      }, {
         "event_name": "windows.onRemoved",
         "filter": {
         },
         "is_for_service_worker": true,
         "is_lazy": false,
         "url": "chrome-extension://jgfbgkjjlonelmpenhpfeeljjlcgnkpe/"
      } ]
   },
   "guid": "4f4a75b3-9c30-4a2f-b19a-2df6917bd153",
   "id": "jgfbgkjjlonelmpenhpfeeljjlcgnkpe",
   "location": "EXTERNAL_POLICY_DOWNLOAD",
   "manifest_version": 3,
   "name": "ClassLink OneClick Extension",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/jgfbgkjjlonelmpenhpfeeljjlcgnkpe/12.5_0",
   "permissions": {
      "active": {
         "api": [ "activeTab", "idle", "storage", "tabs", "webNavigation", "scripting" ],
         "explicit_hosts": [ "*://*/*", "http://*.classlink.com/*", "https://*.classlink.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [ "*://*/*" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "12.5"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 14,
      "listeners": [ {
         "event_name": "input.ime.onActivate",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "input.ime.onBlur",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "input.ime.onCandidateClicked",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "input.ime.onDeactivated",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "input.ime.onMenuItemActivated",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "input.ime.onReset",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "input.ime.onSurroundingTextChanged",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "inputMethodPrivate.onFocus",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "inputMethodPrivate.onScreenProjectionChanged",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "inputMethodPrivate.onSuggestionsChanged",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "system.display.onDisplayChanged",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "types.ChromeSetting.spokenFeedback.onChange",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "virtualKeyboardPrivate.onKeyboardClosed",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "virtualKeyboardPrivate.onKeyboardConfigChanged",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      } ]
   },
   "guid": "cbfaadf9-4331-4ff2-a23c-53d8e8931c37",
   "id": "jkghodnilhceideoidjikpgommlajknk",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Chrome OS XKB",
   "path": "/usr/share/chromeos-assets/input_methods/input_tools",
   "permissions": {
      "active": {
         "api": [ "accessibilityFeatures.read", "app.window.alpha", "audioCapture", "app.window.ime", "input", "inputMethodPrivate", "metricsPrivate", "notifications", "system.display", "tabs", "tts", "unlimitedStorage", "virtualKeyboardPrivate" ],
         "explicit_hosts": [ "https://clients4.google.com/*", "https://dl.google.com/*", "https://edgedl.me.gvt1.com/*", "https://handwriting.googleapis.com/*", "https://www.googleapis.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.0.5.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "537f0758-a3f5-4a5c-b764-044275c798e3",
   "id": "kddnkjkcjddckihglkfcickdhbmaodcn",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Chrome Goodies",
   "path": "/usr/share/chromeos-assets/echo",
   "permissions": {
      "active": {
         "api": [ "alarms", "chromeosInfoPrivate", "cookies", "echoPrivate", "metricsPrivate", "notifications", "storage" ],
         "explicit_hosts": [ "https://*/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.0.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 20,
      "listeners": [ {
         "event_name": "accessibilityPrivate.onSelectToSpeakContextMenuClicked",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "accessibilityPrivate.onSelectToSpeakKeysPressedChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "accessibilityPrivate.onSelectToSpeakMouseChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "accessibilityPrivate.onSelectToSpeakPanelAction",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "accessibilityPrivate.onSelectToSpeakStateChangeRequested",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAccessibilityEvent",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAccessibilityTreeDestroyed",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAccessibilityTreeSerializationError",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onActionResult",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onAllAutomationEventListenersRemoved",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onChildTreeID",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onGetTextLocationResult",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onNodesRemoved",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "automationInternal.onTreeChange",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "clipboard.onClipboardDataChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "contextMenus",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "settingsPrivate.onPrefsChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "storage.onChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "tts.onEvent",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      }, {
         "event_name": "tts.onVoicesChanged",
         "is_for_service_worker": false,
         "is_lazy": false,
         "url": ""
      } ]
   },
   "guid": "32bf22fe-6f14-428a-82dd-c398767104ee",
   "id": "klbcgckkldhdhonijdbnhhaiedfkllef",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Select-to-speak",
   "path": "/opt/google/chrome/resources/chromeos/accessibility",
   "permissions": {
      "active": {
         "api": [ "accessibilityPrivate", "clipboardRead", "clipboardWrite", "commandLinePrivate", "contextMenus", "metricsPrivate", "settingsPrivate", "storage", "tabs", "tts" ],
         "explicit_hosts": [ "https://docs.google.com/*", "https://docs.sandbox.google.com/*" ],
         "manifest": [ {
            "automation": {
               "desktop": true
            }
         } ],
         "scriptable_hosts": [ "https://docs.google.com/document*", "https://docs.sandbox.google.com/document*" ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "137.0.7151.137"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "8d2b24ff-202a-4e04-bd4c-22246745ccfe",
   "id": "komhbcfkdcgmcdoenjcjheifdiabikfi",
   "location": "INTERNAL",
   "manifest_version": 2,
   "name": "Google Play",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/komhbcfkdcgmcdoenjcjheifdiabikfi/3.1_0",
   "permissions": {
      "active": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_HOSTED_APP",
   "version": "3.1"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "79fd8b96-07cd-4d03-80ba-5ccffec7a1af",
   "id": "mfhehppjhmmnlfbbopchdfldgimhfhfk",
   "location": "EXTERNAL_POLICY_DOWNLOAD",
   "manifest_version": 2,
   "name": "Google Classroom",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/mfhehppjhmmnlfbbopchdfldgimhfhfk/1.8_0",
   "permissions": {
      "active": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_HOSTED_APP",
   "version": "1.8"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "d4d2b41e-415d-4178-8550-e09b85470ff6",
   "id": "mgndgikekgjfcpckkfioiadnlibdjbkf",
   "location": "COMPONENT",
   "manifest_version": 1,
   "name": "Chrome",
   "path": "/opt/google/chrome/resources/chrome_app",
   "permissions": {
      "active": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_HOSTED_APP",
   "version": "0.1"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "eae7b08e-eb10-4762-9372-24fb5306ce54",
   "id": "mhjfbmdgcfjbbpaeojofohoefgiehjai",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Chrome PDF Viewer",
   "path": "/opt/google/chrome/resources/pdf",
   "permissions": {
      "active": {
         "api": [ "contentSettings", "fileSystem", "fileSystem.write", "metricsPrivate", "tabs", "resourcesPrivate", "pdfViewerPrivate" ],
         "explicit_hosts": [ "chrome://resources/*", "chrome://webui-test/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 0,
      "listeners": [  ]
   },
   "guid": "f9eeac3b-ceae-45f9-b2ca-7c3aff7a32f9",
   "id": "mppnpdlheglhdfmldimlhpnegondlapf",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "__MSG_chos_inputtool_title__",
   "path": "/opt/google/chrome/resources/keyboard",
   "permissions": {
      "active": {
         "api": [ "inputMethodPrivate", "tabs", "virtualKeyboardPrivate" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.0.6.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 1,
      "listeners": [ {
         "event_name": "app.runtime.onLaunched",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      } ]
   },
   "guid": "ddc14cfd-bfae-41c3-a308-e551d06aa016",
   "id": "nihhbejdflkeingkkpakffdlmepaeaah",
   "location": "INTERNAL",
   "manifest_version": 2,
   "name": "ScanQR",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/nihhbejdflkeingkkpakffdlmepaeaah/0.0.4.0_0",
   "permissions": {
      "active": {
         "api": [ "videoCapture" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_PLATFORM_APP",
   "version": "0.0.4.0"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 1,
      "listeners": [ {
         "event_name": "runtime.onConnectExternal",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      } ]
   },
   "guid": "dafbb43c-9799-4d82-bea1-b9b35cd42572",
   "id": "nkeimhogjdpnpccoofpliimaahmaaome",
   "location": "COMPONENT",
   "manifest_version": 2,
   "name": "Google Hangouts",
   "path": "/opt/google/chrome/resources/hangout_services",
   "permissions": {
      "active": {
         "api": [ "processes", "webrtcLoggingPrivate", "system.cpu", "enterprise.hardwarePlatform" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "1.3.24"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "creation_flags": [ "REQUIRE_KEY", "FROM_WEBSTORE", "WAS_INSTALLED_BY_DEFAULT" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 2,
      "listeners": [ {
         "event_name": "app.runtime.onLaunched",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      }, {
         "event_name": "runtime.onConnectExternal",
         "is_for_service_worker": false,
         "is_lazy": true,
         "url": ""
      } ]
   },
   "guid": "bf3640be-38d4-4e8b-a16b-4367d23c4da9",
   "id": "nmmhkkegccagdldgiimedpiccmgmieda",
   "location": "EXTERNAL_COMPONENT",
   "manifest_version": 2,
   "name": "Chrome Web Store Payments",
   "path": "/home/chronos/u-9f2e37a10f24b980915727b947ebc0670327b84b/Extensions/nmmhkkegccagdldgiimedpiccmgmieda/1.0.0.6_0",
   "permissions": {
      "active": {
         "api": [ "identity", "webview" ],
         "explicit_hosts": [ "https://payments.google.com/*", "https://sandbox.google.com/*", "https://www.google.com/*", "https://www.googleapis.com/*" ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_PLATFORM_APP",
   "version": "1.0.0.6"
}, {
   "background_page_keepalives": {
      "activites": [  ],
      "count": -1
   },
   "creation_flags": [ "REQUIRE_KEY" ],
   "disable_reasons": [  ],
   "event_listeners": {
      "count": 1,
      "listeners": [ {
         "event_name": "runtime.onConnectNative",
         "is_for_service_worker": true,
         "is_lazy": true,
         "url": "chrome-extension://pmfjbimdmchhbnneeidfognadeopoehp/"
      } ]
   },
   "guid": "a6fb2196-8051-4011-962b-e3bed0e34d4f",
   "id": "pmfjbimdmchhbnneeidfognadeopoehp",
   "location": "COMPONENT",
   "manifest_version": 3,
   "name": "Image loader",
   "path": "/opt/google/chrome/resources/image_loader",
   "permissions": {
      "active": {
         "api": [ "nativeMessaging", "offscreen", "imageLoaderPrivate" ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "optional": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      },
      "tab_specific": {
      },
      "withheld": {
         "api": [  ],
         "explicit_hosts": [  ],
         "manifest": [  ],
         "scriptable_hosts": [  ]
      }
   },
   "service_worker_keepalives": {
      "activites": [  ],
      "count": 0
   },
   "type": "TYPE_EXTENSION",
   "version": "0.5"
} ]
