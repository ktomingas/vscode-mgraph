<!-- HEADER -->
<p style='text-align: center;'>
  <img src="https://raw.githubusercontent.com/ktomingas/vscode-mgraph/main/media/mgraph.png" />
</p>
<hr/>

<p style='text-align: center;'>

[![Docs](https://img.shields.io/badge/docs-here-blueviolet?style=for-the-badge)](https://raw.githubusercontent.com/ktomingas/vscode-mgraph/main/README.md)
[![GitHub](https://img.shields.io/github/license/mtxr/vscode-sqltools?style=for-the-badge)](hhttps://raw.githubusercontent.com/ktomingas/vscode-mgraph/main/LICENSE.md)

</p>

**mGRAPH** is meta graph browser for Postgres DB with MMX physical DB schema.

## Features

Main features provided by mGraph:
- DB Physical Model for db schema visualisation as diagram
- Meta Model for logical metamodel visualisation as diagram
- Instance Model for model visualisation as diagram
- Instance Model Graph for system intance type level data flow graph
- Instance Data Graph for intance object level data flow graph

## Usage
Press cmd+shft+p (mac) or cntr+shft+p (win) and type 'MG' to see and select the visualisation provided by extension: 
\!\[Graph\]\(media/usage1.png\)
<!-- <img src="https://raw.githubusercontent.com/ktomingas/vscode-mgraph/main/media/usage1.png" /> -->

## Requirements

This VS Code extension depends on [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) extension that has to be installed and configured with working Postgres DB connection.

## Extension Settings

**mGRAPH** extension has following settings (reload required):
* `general.ModelName`: Default logical model ID for Meta Model
* `general.ObjectId`: Default focus object ID for Instance Graph
* `general.SchemaName`: Default Postgres DB schema name for Physical Model
* `general.SysName`: Default System Origin Name for Instance Model Graph
* `general.SysNamePattern`: Default System Origin pattern for Instance Model
* `query.ExcludeNamePattern`: Default object name pattern to exlude in Physical Model
* `query.ExcludeTypes`: Default object type list to exclude in System and Instance Graph
* `query.IncludePattern`: Default object name pattern to include in Physical Model
* `query.ShowAllObjectTypes`: Query option to show all types (true) or graph connected types (false) in Graph
* `query.ShowMaxDistance`: Query option for horisontal navigation depth or distance in Instance Graph
* `query.ShowModelRelations`: Query option to show model or instance model relation (true) in logical and instance Models
* `query.ShowParentCildRelations`: Query option to show parent-child hierarchy relations (true) or not (false) in Graph

## Changelog

See changelog [here](https://raw.githubusercontent.com/ktomingas/vscode-mgraph/main/CHANGELOG.md)

## Feedback

Please provide feedback through the [GitHub Issue](https://github.com/ktomingas/vscode-mgraph/issues) system.
