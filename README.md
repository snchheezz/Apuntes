# Apuntes
{
  "github": {
    "branch": "main",
    "automaticallyMergePR": true,
    "dryRun": {
      "enable": false,
      "folderName": "github-publisher"
    },
    "tokenPath": "%configDir%/plugins/%pluginID%/env",
    "api": {
      "tiersForApi": "Github Free/Pro/Team (default)",
      "hostname": ""
    },
    "workflow": {
      "commitMessage": "[PUBLISHER] Merge",
      "name": ""
    },
    "verifiedRepo": true
  },
  "upload": {
    "behavior": "fixed",
    "defaultName": "",
    "rootFolder": "",
    "yamlFolderKey": "",
    "frontmatterTitle": {
      "enable": false,
      "key": "title"
    },
    "replaceTitle": [],
    "replacePath": [],
    "autoclean": {
      "enable": false,
      "excluded": []
    },
    "folderNote": {
      "enable": false,
      "rename": "index.md",
      "addTitle": {
        "enable": false,
        "key": "title"
      }
    },
    "metadataExtractorPath": ""
  },
  "conversion": {
    "hardbreak": false,
    "dataview": true,
    "censorText": [],
    "tags": {
      "inline": false,
      "exclude": [],
      "fields": []
    },
    "links": {
      "internal": false,
      "unshared": false,
      "wiki": false,
      "slugify": "disable"
    }
  },
  "embed": {
    "attachments": true,
    "overrideAttachments": [],
    "keySendFile": [],
    "notes": false,
    "folder": "",
    "convertEmbedToLinks": "keep",
    "charConvert": "->",
    "useObsidianFolder": true
  },
  "plugin": {
    "shareKey": "share",
    "excludedFolder": [],
    "copyLink": {
      "enable": false,
      "links": "",
      "removePart": [],
      "transform": {
        "toUri": true,
        "slugify": "lower",
        "applyRegex": []
      }
    },
    "setFrontmatterKey": "Set"
  }
}
