# Graph Report - Water  (2026-09-13)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 426 nodes · 530 edges · 17 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- dependencies
- dependencies
- com.unity.modules.imgui
- com.unity.mathematics
- manifest.json
- packages-lock.json
- com.unity.test-framework
- com.unity.modules.jsonserialize
- com.unity.modules.audio
- com.unity.modules.unitywebrequest
- com.unity.render-pipelines.core
- ReadmeEditor
- com.unity.modules.ui
- com.unity.modules.physics
- com.unity.modules.imageconversion
- com.unity.ai.navigation
- com.unity.collab-proxy

## God Nodes (most connected - your core abstractions)
1. `ReadmeEditor` - 16 edges
2. `com.unity.modules.jsonserialize` - 15 edges
3. `com.unity.modules.physics` - 12 edges
4. `com.unity.modules.unitywebrequest` - 11 edges
5. `com.unity.modules.audio` - 10 edges
6. `com.unity.modules.imageconversion` - 9 edges
7. `com.unity.modules.imgui` - 9 edges
8. `com.unity.mathematics` - 9 edges
9. `com.unity.render-pipelines.core` - 8 edges
10. `com.unity.modules.ui` - 8 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (17 total, 0 thin omitted)

### Community 0 - "dependencies"
Cohesion: 0.04
Nodes (46): dependencies, com.unity.ai.navigation, com.unity.collab-proxy, com.unity.ide.rider, com.unity.ide.visualstudio, com.unity.inputsystem, com.unity.modules.accessibility, com.unity.modules.adaptiveperformance (+38 more)

### Community 1 - "dependencies"
Cohesion: 0.06
Nodes (35): dependencies, depth, source, version, depth, source, version, dependencies (+27 more)

### Community 2 - "com.unity.modules.imgui"
Cohesion: 0.07
Nodes (31): dependencies, depth, source, url, version, dependencies, depth, source (+23 more)

### Community 3 - "com.unity.mathematics"
Cohesion: 0.07
Nodes (30): dependencies, depth, source, url, version, dependencies, depth, source (+22 more)

### Community 4 - "manifest.json"
Cohesion: 0.07
Nodes (28): com.unity.modules.imgui, com.unity.modules.jsonserialize, com.unity.modules.physics, com.unity.modules.unitywebrequestassetbundle, com.unity.ai.navigation, com.unity.collab-proxy, com.unity.ide.rider, com.unity.ide.visualstudio (+20 more)

### Community 5 - "packages-lock.json"
Cohesion: 0.07
Nodes (27): com.unity.modules.ai, com.unity.modules.animation, com.unity.modules.assetbundle, com.unity.modules.audio, com.unity.modules.director, com.unity.modules.imageconversion, com.unity.modules.particlesystem, com.unity.modules.physics2d (+19 more)

### Community 6 - "com.unity.test-framework"
Cohesion: 0.07
Nodes (28): dependencies, depth, source, version, dependencies, depth, source, url (+20 more)

### Community 7 - "com.unity.modules.jsonserialize"
Cohesion: 0.08
Nodes (26): dependencies, dependencies, depth, source, version, dependencies, depth, source (+18 more)

### Community 8 - "com.unity.modules.audio"
Cohesion: 0.08
Nodes (26): dependencies, depth, source, version, dependencies, depth, source, version (+18 more)

### Community 9 - "com.unity.modules.unitywebrequest"
Cohesion: 0.09
Nodes (25): dependencies, depth, source, version, dependencies, depth, source, version (+17 more)

### Community 10 - "com.unity.render-pipelines.core"
Cohesion: 0.09
Nodes (25): depth, source, version, dependencies, depth, source, version, dependencies (+17 more)

### Community 11 - "ReadmeEditor"
Cohesion: 0.12
Nodes (14): ReadmeEditor, BodyStyle, ButtonStyle, HeadingStyle, LinkStyle, TitleStyle, Readme, Section (+6 more)

### Community 12 - "com.unity.modules.ui"
Cohesion: 0.10
Nodes (21): dependencies, depth, source, version, dependencies, depth, source, version (+13 more)

### Community 13 - "com.unity.modules.physics"
Cohesion: 0.10
Nodes (20): dependencies, depth, source, version, dependencies, depth, source, version (+12 more)

### Community 14 - "com.unity.modules.imageconversion"
Cohesion: 0.13
Nodes (15): dependencies, depth, source, version, dependencies, depth, source, version (+7 more)

### Community 15 - "com.unity.ai.navigation"
Cohesion: 0.18
Nodes (11): dependencies, depth, source, url, version, dependencies, depth, source (+3 more)

### Community 16 - "com.unity.collab-proxy"
Cohesion: 0.33
Nodes (6): dependencies, depth, source, url, version, com.unity.collab-proxy

## Knowledge Gaps
- **294 isolated node(s):** `Section`, `com.unity.ai.navigation`, `com.unity.collab-proxy`, `com.unity.ide.rider`, `com.unity.ide.visualstudio` (+289 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 300 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `dependencies` connect `dependencies` to `com.unity.modules.imgui`, `com.unity.mathematics`, `packages-lock.json`, `com.unity.test-framework`, `com.unity.modules.jsonserialize`, `com.unity.modules.audio`, `com.unity.modules.unitywebrequest`, `com.unity.render-pipelines.core`, `com.unity.modules.ui`, `com.unity.modules.physics`, `com.unity.modules.imageconversion`, `com.unity.ai.navigation`, `com.unity.collab-proxy`?**
  _High betweenness centrality (0.793) - this node is a cross-community bridge._
- **Why does `dependencies` connect `dependencies` to `manifest.json`?**
  _High betweenness centrality (0.189) - this node is a cross-community bridge._
- **Why does `com.unity.modules.jsonserialize` connect `com.unity.modules.jsonserialize` to `dependencies`, `com.unity.modules.imgui`, `com.unity.mathematics`, `com.unity.test-framework`, `com.unity.modules.ui`?**
  _High betweenness centrality (0.031) - this node is a cross-community bridge._
- **What connects `Section`, `com.unity.ai.navigation`, `com.unity.collab-proxy` to the rest of the system?**
  _294 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `dependencies` be split into smaller, more focused modules?**
  _Cohesion score 0.043478260869565216 - nodes in this community are weakly interconnected._
- **Should `dependencies` be split into smaller, more focused modules?**
  _Cohesion score 0.058823529411764705 - nodes in this community are weakly interconnected._
- **Should `com.unity.modules.imgui` be split into smaller, more focused modules?**
  _Cohesion score 0.06666666666666667 - nodes in this community are weakly interconnected._