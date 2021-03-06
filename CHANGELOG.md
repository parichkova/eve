# Eve Changelog

## 1.8.0 (04 July 2018)

### Added
- Add new component [Color Picker](https://kanbanize.github.io/eve/documentation/#components/color-picker)

### Changed
- Change tooltip font-size from .875rem to .75rem

### Fixed
- Fix tooltip overflow

### Removed
- Remove ```.is-normal``` avatar

---

## 1.7.0 (15 June 2018)

### Added
- Add accordion with icon
- Add button with icon
- Add profile with icon
- Add ```.is-huge``` avatar

### Changed
- Change accordion visualization

### Fixed
- Fix grid columns responsiveness on small screens

---

## 1.6.0 (11 June 2018)

### Changed
- Change ```px``` to ```rem```

### Removed
- Remove ```.eve-avatar-x-tiny``` from avatars
- Remove ```.eve-avatar-x-large``` from avatars
- Remove ```.eve-text-tiny``` from text utilities

---

## 1.5.0 (8 June 2018)

### Added
- Add text utility ```.eve-text-justify```
- Add new utility [Float](https://kanbanize.github.io/eve/documentation/#utilities/float)

### Changed
- Change accordion header color
- Change ```.eve-text-mute``` to ```.eve-text-muted```
- Change ```.eve-grid``` to ```.eve-row```
- Change ```.eve-cell``` to ```.eve-column```
- Change ```.eve-cell-{number}``` to `.eve-column.is-{number}`

```html
// Before
<div class="eve-grid">
    <div class="eve-cell-4"></div>
</div>

// After
<div class="eve-row">
    <div class="eve-column is-4"><div>
</div>
```

### Fixed
- Fix dropdown active element background color

### Removed
- Remove ```.eve-overflow-visible``` from overflow utilities
- Remove ```.eve-display-inline-flex``` from display utilities
- Remove ```.eve-display-flex``` from display utilities

---

## 1.4.5 (5 June 2018)

### Changed
- Change navigation items height

### Fixed
- Fix navigation item text overflow
- Fix select arrow in Internet Explorer
- Fix table word wrap
- Fix accordion header font size

### Removed
- Remove background color in navigation
- Remove background color in tabs
