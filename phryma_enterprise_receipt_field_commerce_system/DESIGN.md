---
name: Phryma Enterprise Receipt & Field Commerce System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#43474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777e'
  outline-variant: '#c3c6ce'
  surface-tint: '#49607c'
  primary: '#001428'
  on-primary: '#ffffff'
  primary-container: '#0f2942'
  on-primary-container: '#7991af'
  inverse-primary: '#b0c9e8'
  secondary: '#006b53'
  on-secondary: '#ffffff'
  secondary-container: '#76f6cd'
  on-secondary-container: '#007057'
  tertiary: '#280030'
  on-tertiary: '#ffffff'
  tertiary-container: '#490057'
  on-tertiary-container: '#c46ed0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4ff'
  primary-fixed-dim: '#b0c9e8'
  on-primary-fixed: '#011d35'
  on-primary-fixed-variant: '#314863'
  secondary-fixed: '#79f9d0'
  secondary-fixed-dim: '#59dcb5'
  on-secondary-fixed: '#002117'
  on-secondary-fixed-variant: '#00513e'
  tertiary-fixed: '#ffd6ff'
  tertiary-fixed-dim: '#f8acff'
  on-tertiary-fixed: '#350040'
  on-tertiary-fixed-variant: '#722181'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Outfit
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Outfit
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Outfit
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  fiscal-numeral-lg:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.03em
  fiscal-numeral-md:
    fontFamily: JetBrains Mono
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.02em
  receipt-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 15px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-xxs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-base: 1rem
  space-lg: 1.25rem
  space-xl: 1.5rem
  space-2xl: 2rem
  space-3xl: 3rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  margin-mobile: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
---

## Brand & Style

This design system delivers an authoritative, high-trust fiscal experience tailored for Phryma S.A.C.'s commercial agents and billing operations in Peru. Designed primarily for rugged, mobile-first field environments and enterprise back-office reconciliation, the visual aesthetic merges strict corporate reliability with tactical fiscal clarity. 

The design narrative is built on precision, institutional trust, and high legibility under harsh lighting conditions (such as outdoor dispatch, market stalls, and warehouse delivery bays). The interface integrates tactile receipt elements—such as precision dotted perforations, digital watermarks, security guilloche micro-borders, and formalized official stamp motifs—without veering into pastiche. It upholds a crisp, modernized enterprise aesthetic balancing administrative formality with rapid, friction-free transaction entry.

## Colors

The palette establishes immediate fiscal authority through deep naval slate, energized by an audit-grade fiscal teal and targeted transaction identity tokens:

- **Primary (`#0F2942`)**: Deep Navy Slate. Serves as the primary operational surface, anchor text, primary button background, and formal institutional header background. It communicates institutional weight, legal stability, and compliance.
- **Secondary (`#00A884`)**: Fiscal Teal / Mint Accent. Applied to valid transaction triggers, successful SUNAT verification badges, active status indicators, and positive balances. High legibility against both white and dark slate backdrops.
- **Tertiary (`#732282`)**: Peruvian Fiscal Accent (Yape Purple). Specifically designated for payment channel recognition (Yape), mobile wallet tags, and rapid reconciliation callouts. Paired with secondary payment anchors: Plin Cyan (`#00A8E8`), BCP Safety Orange (`#FF7800`), and Cash/Efectivo Emerald (`#107C41`).
- **Neutral (`#64748B`)**: Slate Blue Steel. Guides structured borders, muted receipt metadata, currency prefixes, unselected tabs, and secondary labels.
- **Surface Foundations**:
  - `surface-canvas`: `#F4F6F9` (cool, anti-glare enterprise grey-slate base)
  - `surface-card`: `#FFFFFF` (pure white for receipts and interactive cards)
  - `surface-container-low`: `#E9EEF4` (recessed input fields and inactive payment chips)
  - `surface-receipt`: `#FAFCFD` (subtle paper-tinted card container for digital receipts)
- **High-Contrast Fiscal Tokens**:
  - `status-error`: `#DC2626` (rejected receipt, SUNAT communication error)
  - `status-warning`: `#D97706` (pending synchronization, offline ledger mode)
  - `stamp-ink`: `#1D4ED8` (official company seal / authorized stamp pigment)

## Typography

The typographic hierarchy uses a triad structure engineered for commercial velocity, absolute monetary legibility, and regulatory compliance:

1. **Brand & Operational Headers (`Outfit`)**: Clean geometric construction giving modern authority to view titles, client billing summaries, and screen banners.
2. **System Interface & Field Body (`Inter`)**: High-x-height utilitarian sans-serif used across all forms, client records, addresses, and status messaging. Maintains sharp contrast even on anti-glare mobile screen protectors in direct sunlight.
3. **Monetary Values & Hash Codes (`JetBrains Mono`)**: Strict tabular alignment applied to currency notations (PEN `S/.`, USD `$`), transaction IDs, RUC numbers, and electronic invoice hash codes (SUNAT digest codes). Figures align vertically in multi-item receipt tables without dynamic shift or misinterpretation.

## Layout & Spacing

The layout model adheres to an 8px base rhythm with a strict 4px sub-grid for dense financial tables, receipt line items, and nested payment badges.

- **Mobile Viewports (Field Agent Terminal, 360px - 599px)**:
  - 4-column fluid layout with `16px` outer margins and `12px` gutters.
  - Receipt items snap to full width; primary monetary actions stick to bottom thumb-zones with fixed `56px` hit targets.
- **Tablet Viewports (POS Stand / Countertop, 600px - 1023px)**:
  - 8-column layout with `24px` outer margins and `16px` gutters.
  - Split-pane layout: Left pane for inventory/catalog selection (5 columns), right pane for live receipt preview and payment processing (3 columns).
- **Desktop Viewports (Audit & Accounting Console, >= 1024px)**:
  - 12-column layout with max-width `1440px`, centered with `40px` margins and `24px` gutters.
  - Master-detail ledger views, side-by-side reconciliation drawers, and fiscal batch audit queues.

## Elevation & Depth

To prevent visual noise during fast-paced field transactions, depth is established primarily through **Tonal Layering** combined with **Low-Contrast Technical Outlines** and purposeful tactile shadows:

- **Level 0 (Floor Canvas)**: `#F4F6F9`. Clean, anti-fatigue base background for views.
- **Level 1 (Card & Paper Surfaces)**: `#FFFFFF` with a crisp `1px` border using `rgba(15, 41, 66, 0.08)`. No blur shadow; clarity is defined by the sharp border contrast.
- **Level 2 (Receipt Floating Sheet & Modals)**: Digital receipts use a paper surface layer lifted by a dual-axis ambient shadow: `0 4px 16px -2px rgba(15, 41, 66, 0.08), 0 1px 3px 0 rgba(15, 41, 66, 0.04)`.
- **Level 3 (Payment Bottom Drawers & Action Bars)**: `0 -4px 20px 0 rgba(15, 41, 66, 0.12)`, grounding bottom action sheets firmly above list content.
- **Tactile Receipt Perforations**: Dotted separator lines are rendered using SVG masking or crisp `2px` dashed rules with `#CBD5E1` to indicate detachable tear-off vouchers.
- **Security Stamp Layer**: Official stamps (e.g., "CANCELADO / PHRYMA S.A.C.", "SUNAT APROBADO") are placed at a -8-degree rotation with an opacity of `0.92`, multiply-blended over receipt totals to emulate physical ink stamping.

## Shapes

The design system adopts a **Rounded (`2`)** shape personality for primary enterprise containers, balanced by tighter geometric radii for inner receipt components:

- **Cards & Primary Modules**: `16px` (`rounded-lg`) to `24px` (`rounded-xl`). Creates friendly, modern card contours that soften dense enterprise ledger views.
- **Buttons, Modals & Floating Drawers**: `12px` to `16px` for comfortable touch ergonomics on handheld commercial devices.
- **Badges, Payment Tags & Status Pills**: Full pill shape (`9999px`) for quick scanning.
- **Receipt Body Core**: `12px` top corners, featuring jagged/scalloped micro-cut or perforated styling on the bottom tear edge for voucher detachment flows.
- **Signature Box**: `8px` rounded perimeter with an interior flat boundary for clean stylus and fingertip sign-offs.

## Components

### Buttons
- **Primary Operational (`Btn-Emitir-Comprobante`)**: Solid `#0F2942` with `#FFFFFF` text, `48px` minimum height, `12px` border radius, font `label-lg`. Tap state transitions to `#0A1C2E` with an inner shadow.
- **Secondary Fiscal Action**: Border `1.5px` solid `#00A884`, transparent or `#00A884`/`8%` background, `#00A884` text. Used for "Enviar por WhatsApp", "Descargar PDF", and "Duplicado".
- **Destructive/Void**: Border `1px` solid `#FCA5A5`, `#FEF2F2` background, `#DC2626` text. Used for "Anular Boleta / Factura".

### Payment Channel Badges
- **Yape**: Background `#F3E8F7`, border `#732282`/`25%`, text `#732282`, featuring circular mini-glyph.
- **Plin**: Background `#E0F7FF`, border `#00A8E8`/`30%`, text `#007AAB`.
- **Transferencia (BCP/BBVA/Interbank)**: Background `#EFF6FF`, border `#3B82F6`/`25%`, text `#1D4ED8`.
- **Efectivo (Cash)**: Background `#ECFDF5`, border `#10B981`/`30%`, text `#065F46`.
- *Interaction*: Tap-to-toggle mode allows single or split-tender payments with instant visual checkmarks.

### Receipt Card (`Receipt-Slip`)
- Upper section contains Phryma S.A.C. header, RUC `20XXXXXXXXX`, official serial code (e.g., `B001-0004921`), and client name.
- Middle body separated by a dotted perforation line (`border-t-2 border-dashed border-slate-300`).
- Line-item breakdown formatted in tabular JetBrains Mono font: Quantity, Description, IGV (18%), and Total.
- Stamp overlay zone: angled monochrome ink stamp (`#1D4ED8` or `#00A884`) verifying payment registration.
- Lower stub includes QR code (SUNAT electronic standard) and a 40-character fiscal hash string.

### Form Inputs & Currency Fields
- **Amount Input (`Input-Monto`)**: Elevated numeric field with persistent currency prefix (`S/.` or `$`), rendered in `fiscal-numeral-lg`, right-aligned, zero-flicker tabular display.
- **Search & Auto-Complete (RUC / DNI)**: Integrates SUNAT API sync state indicator (pulsing teal dot for verified taxpayer status; amber dot for non-habido).

### Checkboxes & Segmented Selectors
- Checkbox elements use a `20px` square with `4px` corner radius, `#0F2942` fill when checked with a crisp white checkmark.
- Segmented invoice switch ("Boleta" vs. "Factura" vs. "Nota de Venta") structured inside an encapsulated slate track with fluid highlight slider.

### Digital Signature Pad Component
- Dedicated clean canvas container with `#F8FAFC` background, subtle watermark "Firma del Cliente", clear button top-right, and bottom compliance disclaimer label (`body-sm`).