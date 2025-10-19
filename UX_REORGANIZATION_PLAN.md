# PlanNet UI/UX Reorganization Plan

## Executive Summary

This document outlines a comprehensive plan to reorganize PlanNet's current overlay-based menu system into a more intuitive, efficient sidebar-based layout following proven UX principles.

## Current UI Structure Analysis

The current system uses an overlay-based menu with **13 main feature categories**:

### Core Features:
1. **Edit_Profile** - Profile management, domain registration, topic creation
2. **load** - Data loading from topics/domains, message filtering  
3. **upload-to-ipfs** - File upload/download via IPFS
4. **create** - Topic creation with admin controls
5. **marker** - Geographic marker placement system
6. **polygon** - Geographic polygon drawing system 
7. **rules** - Topic rules and moderation controls
8. **utility** - NFT utilities and model management
9. **memo** - Chat systems (both public and encrypted)

### UI Customization:
10. **model** - 3D model controls and settings
11. **main-button** - Button styling controls
12. **marker-options** - Marker appearance settings  
13. **topic-chat** - Chat appearance customization

## UX Problems with Current Structure

1. **Cognitive Overload** - 13 separate overlay panels create menu fatigue
2. **No Information Hierarchy** - All features treated equally regardless of frequency/importance
3. **Workflow Disruption** - Related features scattered across different panels
4. **Discovery Issues** - Hidden overlay system makes features hard to find
5. **Spatial Inefficiency** - Overlay panels block the main workspace

## Proven UX Principles for Reorganization

1. **Progressive Disclosure** - Show primary functions first, secondary on demand
2. **Functional Grouping** - Group related features by workflow context  
3. **Frequency-Based Placement** - Most-used features get prime real estate
4. **Spatial Consistency** - Persistent sidebars vs. disruptive overlays
5. **Visual Hierarchy** - Clear distinction between feature categories

## Proposed Feature Groupings by User Workflow

### PRIMARY WORKFLOW (Left Sidebar)
- **Content Management** - Core data operations users do most frequently
  - Load Data (topic/domain loading)
  - IPFS Upload/Download  
  - Profile Management (domains, topics, usernames)

- **Communication** - Real-time user interaction
  - Topic Chat (public messaging)
  - Encrypted Chat (private messaging)

### SECONDARY WORKFLOW (Right Sidebar)
- **Spatial Tools** - Geographic/3D workspace tools
  - Marker Placement
  - Polygon Drawing  
  - 3D Model Controls

- **Administration** - Governance and utility functions
  - Create Topics (admin setup)
  - Topic Rules (moderation)
  - NFT Utilities

- **Customization** - Appearance and UI settings (collapsible)
  - Interface Styling
  - Chat Appearance
  - Marker/Button Styling

## Left Sidebar Layout Plan (Primary Functions)

### TOP SECTION - Content Management
```
┌─ CONTENT ─────────────────┐
│ 📂 Load Data              │
│   ├ Topic/Domain Input    │  
│   ├ Loaded Topics List    │
│   └ Message Filtering     │
│                           │
│ 📤 IPFS Upload            │
│   ├ File Upload           │
│   ├ CID Input/Output      │
│   └ Content Type Select   │
│                           │  
│ 👤 Profile                │
│   ├ Domain Registration   │
│   ├ Username/Picture      │
│   └ Topic Management      │
└───────────────────────────┘
```

### BOTTOM SECTION - Communication
```
┌─ COMMUNICATION ───────────┐
│ 💬 Topic Chat            │
│   ├ Public Messages       │
│   ├ Time Filtering        │
│   └ User ID Loading       │
│                           │
│ 🔒 Encrypted Chat        │
│   ├ Private Messages      │
│   ├ Time Filtering        │
│   └ Secure Messaging      │
└───────────────────────────┘
```

## Right Sidebar Layout Plan (Secondary Functions)

### TOP SECTION - Spatial Tools
```
┌─ SPATIAL TOOLS ───────────┐
│ 📍 Markers                │
│   ├ Place Markers         │
│   ├ Marker Size/Style     │  
│   └ Delete Markers        │
│                           │
│ 🔲 Polygons               │
│   ├ Draw Polygons         │
│   ├ Polygon Rules         │
│   └ Delete Polygons       │
│                           │
│ 🎮 3D Models              │
│   ├ Add/Remove NFTs       │
│   ├ Scale Controls        │
│   └ Model Settings        │
└───────────────────────────┘
```

### MIDDLE SECTION - Administration
```
┌─ ADMINISTRATION ──────────┐
│ ⚙️ Create Topic           │
│   ├ Admin Setup           │
│   ├ Private Key Entry     │
│   └ Public Key Display    │
│                           │
│ 📜 Topic Rules            │
│   ├ Load Rules            │
│   ├ Rule Management       │
│   └ Moderation Tools      │
│                           │
│ 🎨 NFT Utilities          │
│   ├ NFT Management        │
│   └ Utility Functions     │
└───────────────────────────┘
```

### BOTTOM SECTION - Customization (Collapsible)
```
┌─ CUSTOMIZE ───────────────┐
│ 🎨 Interface (▼)          │
│   ├ Button Colors         │
│   ├ Input Styling         │
│   └ Font Settings         │
│                           │
│ 💬 Chat Styling (▼)       │
│   ├ Username Colors       │
│   ├ Text Colors           │
│   └ Container Styling     │
└───────────────────────────┘
```

## Information Hierarchy & Visual Design

### VISUAL GROUPING STRATEGY:
- **Group Headers** - Clear category titles with icons
- **Progressive Disclosure** - Collapsible sections for less frequent features  
- **Visual Separation** - Distinct spacing between functional groups
- **Contextual Grouping** - Related controls grouped together spatially

### INTERACTION PATTERNS:
- **Persistent Sidebars** - Always available, no overlay disruption
- **Scroll Within Sections** - Handle overflow without losing context
- **Quick Access** - Most frequent features (Load, Chat) prominently placed
- **Advanced Features** - Administrative tools tucked in right sidebar

## Benefits of This Reorganization

1. **Reduced Cognitive Load** - 13 overlays → 6 logical groups
2. **Workflow Efficiency** - Related features physically grouped  
3. **Better Discoverability** - Clear categorization with persistent visibility
4. **Scalability** - Room for new features within logical groups
5. **User Mental Model** - Matches typical productivity app patterns

## Implementation Strategy

### Phase 1: Foundation
- Implement collapsible sidebar panels
- Create visual grouping system with headers and icons
- Establish consistent spacing and typography

### Phase 2: Content Migration
- Migrate content management features to left sidebar
- Implement communication panel in left sidebar
- Test core user workflows

### Phase 3: Secondary Features
- Migrate spatial tools to right sidebar
- Implement administration panel
- Add collapsible customization section

### Phase 4: Polish & Optimization
- Fine-tune visual hierarchy
- Optimize for mobile/tablet responsiveness
- User testing and refinement

## Success Metrics

- **Reduced Time to Task** - Faster access to frequently used features
- **Improved Discoverability** - Users can find features without hunting through overlays
- **Better Task Flow** - Related features grouped for efficient workflows
- **Reduced Learning Curve** - Intuitive organization based on established patterns

---

*This reorganization transforms the current overlay-heavy interface into a modern, efficient workspace that prioritizes user workflow and reduces cognitive overhead.*