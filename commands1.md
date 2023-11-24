<!-- ---
title: Commands1
layout: home
nav_order: 4
--- -->

# Commands

Interaction with the toolkits happens via a command line interface. The commands can be executed in your terminal of choice, a Jupyter Notebook and soon via our API.

## OpenAD

<details markdown="block">
<summary>See commands</summary>

### General

`openad`<br>
Display the openad splash screen.

`get status`<br>
Display the currently selected workspace and toolkit.

`display history`<br>
Display the last 30 commands run in your current workspace.

`clear sessions`<br>
Clear any other sessions that may be running.

<br>

### Queries

`search for '<string>' using (index_key=<index_name> [ page_size=<int> edit_distance=<integer> ]) show (data|docs) [ estimate only|return as data|save as '<csv_filename>' ]`{: .cmd }
Performs a document search of the Deep Search repository based on a given index.Use Estimate only, if you are doing a general search, so as to determine the potential number of hits.

<br>

### Execution:

`exec display_collection()`

</details>

<details markdown="block">
<summary>See general commands</summary>

### General

    openad

Display the openad splash screen.

    get status

Display the currently selected workspace and toolkit.

    display history

Display the last 30 commands run in your current workspace.

    clear sessions

Clear any other sessions that may be running.

</details>
