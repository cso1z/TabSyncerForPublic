# TabSyncer

[View in Chinese](../README.md) | [View in English](README.en.md)

TabSyncer is a Chrome extension suite for managing browser workspaces. It is not only a snapshot saver. Its core loop connects the new tab entry point, Tabout for organizing currently open tabs, the home snapshot list with grouped views, and a relationship graph for rediscovering saved contexts.

The main flow is: start from NewTab, organize currently open tabs with Tabout, save valuable context as snapshots, then manage those snapshots from the home page through lists, groups, search, and the graph view.

---

## Core Workflow

Beyond that core loop, TabSyncer also lets you import the Chrome bookmarks you already have and export saved snapshots to local files after they have been organized, completing the full path of import, organization, preservation, and export.

### 1. Import Chrome Bookmarks: Bring Existing Materials Into The Workspace

If you have already accumulated a large set of bookmarks in Chrome, you can import them directly into TabSyncer and use them as the starting point for further organization, enrichment, and long-term preservation.

![Import Chrome bookmarks](../resource/import-chrome-bookmarks.png)

### 2. NewTab: The Browser Entry Point

TabSyncer can turn Chrome's new tab page into a lightweight workspace:

- Pin frequently used URL shortcuts
- Pin frequently used snapshot shortcuts
- Preview and reopen tabs from a snapshot shortcut
- Continue an unfinished organizer draft
- See recommended snapshots you may want to return to
- Jump into tab organization based on the current window state

![NewTab workspace](../resource/newtab.png)

### 3. Tabout: Organize Currently Open Tabs

The NewTab organizer focuses on the tabs that are open right now:

- Review tabs across the current window and other windows
- Organize by window, groups, similar domains, and duplicate pages
- Pick tabs to keep and close tabs you no longer need
- Save organized selections as new snapshots
- Resume an unfinished organization draft

This solves the moment when the browser has become too noisy and you need to turn the current mess back into a clean workspace.

![Tabout open-tab management](../resource/tabout.png)

### 4. Home: Snapshot List, Groups, And Long-Term Management

The home page is where saved snapshots become durable knowledge:

- View snapshots by all, temporary, group, and trash views
- Manage snapshot groups and grouped snapshot lists
- Search by snapshot name, tab title, URL, and date range
- Rename, delete, restore, merge, and batch-manage snapshots
- Add more web pages to an existing snapshot
- Add a snapshot or a tab inside a snapshot back to NewTab shortcuts

This solves what happens after saving: finding, archiving, merging, and continuing to maintain the context.

![Home snapshot list and groups](../resource/home.png)

### 5. Relationship Graph: Rediscover Snapshot Connections

TabSyncer also provides a snapshot relationship graph:

- Explore snapshots as a connected graph
- Use tags, titles, and URLs to surface related snapshots
- Revisit project research, study material, and long-running browser contexts

This makes snapshots more than a flat list. They can be rediscovered through relationships.

![Snapshot relationship graph](../resource/contextgraph.png)

### 6. Export Snapshots To Local Files: Take Preserved Results With You

Organized snapshots do not have to stay only inside TabSyncer. You can export them to local files for backup, migration, or offline keeping, which closes the loop for this workspace flow.

![Export snapshots to local files](../resource/export-snapshot-local.png)

---

## Key Features

- **One-click snapshots**: Save the current tab, current window, all windows, or split each window into its own snapshot.
- **NewTab workspace**: Search, shortcuts, snapshot entries, and work-continuity prompts in one place.
- **Tabout open-tab management**: Organize currently open tabs, handle duplicates and groups, then save the result.
- **Import Chrome bookmarks**: Bring existing Chrome bookmarks into TabSyncer and turn them into work materials you can keep organizing and preserving.
- **Snapshot list and groups**: Manage snapshots by views and groups for long-term storage.
- **Snapshot relationship graph**: Understand saved contexts from a relationship-based view.
- **Add pages to existing snapshots**: Add an open tab or manually entered URL into an existing snapshot.
- **Export snapshots to local files**: Export saved snapshots to your local device for backup, migration, or offline keeping.
- **Multi-device sync**: Sign in with the same account and sync snapshots across devices.
- **Shortcut maintenance**: Add URLs, snapshots, and individual saved pages to NewTab shortcuts.
- **Recycle bin recovery**: Deleted snapshots are recoverable individually or in batches.
- **Multi-language UI**: Core actions, dialogs, and prompts support multiple languages.

### Import Chrome Bookmarks

You can start by importing the bookmarks you have already accumulated in Chrome, then continue organizing, enriching, and managing them inside TabSyncer as snapshots.

![Import Chrome bookmarks](../resource/import-chrome-bookmarks.png)

### Export Snapshots To Local Files

Saved snapshots do not have to stay only inside TabSyncer. You can export them to local files to complete the full loop from import, organization, and preservation to local export.

![Export snapshots to local files](../resource/export-snapshot-local.png)

---

## Use Cases

### Work Across Devices

Save a set of work tabs at the office, sign in at home, and restore the same context without hunting every page down again.

### Clean Up A Noisy Browser

Open Tabout from NewTab, organize currently open tabs, close duplicates, and save the important context as a snapshot.

### Project Research

Save docs, dashboards, repositories, test environments, and design references as project snapshots that can keep growing over time.

### Rediscover Past Context

Use grouped snapshot lists on the home page, or open the graph view to find related historical material.

---

## Installation

### Option 1: Install From Chrome Web Store

The recommended way is to install TabSyncer directly from Chrome Web Store:

[TabSyncer - Chrome Web Store](https://chromewebstore.google.com/detail/tabsyncer/ngfhokcebemclkfagnkgfficddkmcoim)

### Option 2: Install The Release Package

1. Download `TabSyncer.zip` from this repository or the latest release.
2. Extract `TabSyncer.zip`.
3. Open `chrome://extensions/` in Chrome.
4. Enable Developer mode.
5. Click "Load unpacked".
6. Select the extracted extension directory.

### Option 3: Use The Web Manager

For temporary snapshot viewing or management, you can also open:

[https://www.joker.blue/tab/main](https://www.joker.blue/tab/main)

---

## Usage Flow

1. **Sign in**: Use email verification or GitHub login.
2. **Import existing materials**: Import Chrome bookmarks to quickly bring your previously collected links into the current workspace.
3. **Set up NewTab**: Enable the TabSyncer new tab page and add URL or snapshot shortcuts.
4. **Organize open tabs**: Enter Tabout from NewTab and organize the tabs that are currently open.
5. **Save snapshots**: Save the current window, all windows, or organized selections as snapshots.
6. **Manage snapshots**: Use the home page list, groups, search, merge, and recovery tools.
7. **Open the graph**: Use the relationship graph to understand how snapshots connect.
8. **Export to local files**: Export organized snapshots to local files for backup, migration, or offline keeping.
9. **Continue work**: Restore snapshots from NewTab shortcuts or the home page.

---

## Feedback

Questions, ideas, and pull requests are welcome.

---

## Version Notes

Historical version notes are available in [VERSION.md](VERSION.md).

---

## Join The Community

Join the TabSyncer QQ group to discuss usage tips, share feedback, suggest features, and get early access notes for beta builds. It is a good place for users who want to help shape the browser workspace workflow.

![TabSyncer QQ group](../resource/qq.png)
