---
name: "Neo Studio"
system_slug: "neo-studio"
colors:
  primary: "#AC6AFF"
  secondary: "#BD92FF"
  accent: "#AC6AFF"
  neutral: "#757185"
  background: "#0A0915"
  surface: "#15131D"
  error: "#FF6B7E"
  success: "#5BC489"
  warning: "#FFC861"
  info: "#6BA6FF"
  border: "rgba(255,255,255,0.10)"
  text_primary: "#FFFFFF"
  text_secondary: "#E2DFEC"
  text_tertiary: "#9590A8"
  text_muted: "#5A5567"
  hover_bg: "rgba(172,106,255,0.08)"
  selected_bg: "rgba(172,106,255,0.12)"
  selected_fg: "#AC6AFF"
typography:
  display:
    fontFamily: Sora
    fontSize: 64px
    fontWeight: 700
    tailwind: "font-['Sora'] text-[64px] leading-[72px] font-bold tracking-[-0.03em]"
  heading:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: 700
    tailwind: "font-['Sora'] text-[32px] leading-[40px] font-bold tracking-[-0.03em]"
  subheading:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: 600
    tailwind: "font-['Sora'] text-[20px] leading-[28px] font-semibold tracking-[-0.01em]"
  body:
    fontFamily: Sora
    fontSize: 15px
    fontWeight: 400
    tailwind: "font-['Sora'] text-[15px] leading-[24px]"
  small:
    fontFamily: Sora
    fontSize: 12px
    fontWeight: 400
    tailwind: "font-['Sora'] text-xs text-[#9590A8]"
  label:
    fontFamily: Sora
    fontSize: 12px
    fontWeight: 500
    tailwind: "font-['Sora'] text-xs font-medium uppercase tracking-[0.04em] text-[#9590A8]"
  button:
    fontFamily: Sora
    fontSize: 13px
    fontWeight: 500
    tailwind: "font-['Sora'] text-[13px] font-medium"
  code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: 400
    tailwind: "font-['JetBrains_Mono'] text-[13px] leading-[20px]"
spacing:
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
rounded:
  sm: "6px"
  md: "10px"
  lg: "14px"
  xl: "20px"
  2xl: "28px"
  full: "9999px"
shadows:
  sm: "0 2px 8px rgba(0,0,0,0.30)"
  md: "0 4px 16px rgba(0,0,0,0.40)"
  lg: "0 8px 32px rgba(0,0,0,0.50)"
  xl: "0 16px 48px rgba(0,0,0,0.65)"
  violet_glow: "0 0 0 1px rgba(172,106,255,0.30), 0 8px 28px rgba(172,106,255,0.20)"
  focus_ring: "0 0 0 3px rgba(172,106,255,0.35)"
surfaces:
  card: "bg-[#15131D] border border-white/10 rounded-[14px]"
  input: "h-10 border border-white/10 rounded-[10px] bg-[#1B1A23] px-3 text-[13px] text-white placeholder-[#5A5567]"
  button_primary: "h-9 rounded-[10px] bg-[#AC6AFF] px-4 text-[13px] font-medium text-white"
  button_secondary: "h-9 rounded-[10px] border border-white/10 bg-[#15131D] px-4 text-[13px] font-medium text-white"
  button_ghost: "h-9 rounded-[10px] px-4 text-[13px] font-medium text-[#E2DFEC]"
gradients:
  rainbow: "linear-gradient(90deg, #89F9E8 0%, #FACB7B 35%, #D87CEE 65%, #9099FC 100%)"
  glow_radial: "radial-gradient(60% 80% at 50% 0%, rgba(172,106,255,0.22), transparent 70%)"
---

# Neo Studio Design System

A near-black canvas, a single violet voltage line, and a rainbow gradient kept on a short leash — built for conversations that should feel like the future, not feel like a form. Dark is the canvas; we never go navy, slate, or grey — the violet is louder against true ink. One pulse, not five: violet is the only chromatic accent, status colors whisper, the rainbow gradient is punctuation, never paragraph.

## Overview

Neo Studio is a dark, premium design system built for creative-professional tools — music and video production interfaces, portfolio sites, design platforms, and premium SaaS dashboards. The personality is cinematic and intentional: deep violet-black surfaces establish depth and focus, while a single electric violet accent (`#AC6AFF`) provides all chromatic energy. The system feels like a professional instrument — immersive, distraction-free, and quietly luxurious. Target audience: creative professionals, producers, and designers who expect their tools to look as good as the work they produce.

## Color usage

Electric violet (`#AC6AFF`) is the sole chromatic accent. It is reserved for primary CTAs, active/selected states, links, focus rings, and the signature violet glow. Everything else operates on a near-black-to-white neutral ramp.

- **Primary CTA**: `bg-[#AC6AFF] text-white`, hover `bg-[#BD92FF]`
- **Links**: `text-[#BD92FF]` (lighter violet for readability on dark), hover `text-[#AC6AFF]`
- **Selected/active state**: `bg-[rgba(172,106,255,0.12)] text-[#AC6AFF]` (semi-transparent violet tint)
- **Text hierarchy**: `#FFFFFF` (primary/headings), `#E2DFEC` (secondary/body), `#9590A8` (tertiary/meta), `#5A5567` (muted/placeholders)
- **Backgrounds**: `#0A0915` (page canvas — deepest layer), `#15131D` (cards/panels), `#1B1A23` (subtle emphasis), `#25232E` (muted interactive zones)
- **Hover layer**: `rgba(172,106,255,0.08)` — a barely-visible violet tint for hover warmth
- **Borders**: `rgba(255,255,255,0.06)` (subtle), `rgba(255,255,255,0.10)` (default), `rgba(255,255,255,0.18)` (strong). All semi-transparent white — never solid hex values.
- **Status colors**: success `#5BC489`, warning `#FFC861`, danger `#FF6B7E`, info `#6BA6FF`. Status backgrounds use semi-transparent fills at 12% opacity.

Never introduce a second chromatic color family. Violet is the entire chromatic identity.

## Typography

Primary typeface: Sora — a geometric sans-serif with a modern, slightly rounded character. Code blocks use JetBrains Mono.

The scale: 12px (xs/labels), 13px (sm/buttons), 15px (base/body), 17px (md/subheadings), 20px (lg/section titles), 24px (xl/page headings), 32px (2xl/hero headings), 44px (3xl/display), 64px (4xl/splash).

- **Display/hero**: bold (700), 44-64px, tight tracking (-0.03em)
- **Headings**: bold (700), 20-32px, tight tracking (-0.03em)
- **Body**: regular (400), 15px/24px — generous line height for readability on dark backgrounds
- **Labels/overlines**: medium (500), 12px, uppercase, tracking (0.04em) in `text-[#9590A8]`
- **Buttons and inputs**: medium (500), 13px

## Layout

4px base spacing unit. Standard stops: 8px (xs), 12px (sm), 16px (md), 24px (lg), 32px (xl), 48px (2xl).

- **Card padding**: 24px (p-6)
- **Border radii**: 6px (sm — chips/tags), 10px (md — buttons/inputs), 14px (lg — cards), 20px (xl — modals), 28px (2xl — hero sections)
- **Button height**: 36px default (h-9), 32px small, 44px large
- **Input height**: 40px default (h-10), 32px small, 48px large

Shadows are heavy and dark (rgba black at 30-65% opacity) because they must read on near-black surfaces. The signature decorative element is the **violet glow**: `shadow-[0_0_0_1px_rgba(172,106,255,0.30),0_8px_28px_rgba(172,106,255,0.20)]` — use it on featured cards, hero CTAs, and premium elements. The rainbow gradient (`linear-gradient(90deg, #89F9E8 0%, #FACB7B 35%, #D87CEE 65%, #9099FC 100%)`) is for decorative dividers and premium badges — use sparingly.

## Do's and Don'ts

- Do: use `bg-[#15131D] border border-white/10 rounded-[14px]` for all card surfaces.
- Do: use the violet glow shadow on featured or premium elements — hero CTAs, pricing cards, showcase items. It is the signature flourish.
- Do: use `rgba(172,106,255,0.08)` as the hover background for interactive elements.
- Do: use semi-transparent white borders (`border-white/6`, `border-white/10`, `border-white/18`) instead of solid hex border colors.
- Don't: use solid white for backgrounds or surfaces. White is for text only. All surfaces sit on the ink-to-graphite dark ramp.
- Don't: use solid hex values for borders. Always use `rgba(255,255,255,...)` or Tailwind `border-white/[opacity]`.
- Don't: add light-mode colors or grey backgrounds. This is dark-mode only. The lightest background is `#25232E`.
- Don't: use small border radii (2px, 4px). Minimum is 6px. Cards are 14px, buttons are 10px.
- Don't: use the violet glow on every element. Reserve it for 1-3 featured items per view.
- Don't: use bright status colors at full opacity for backgrounds. Status backgrounds must use 12% opacity semi-transparent fills.

## Token overrides

The following overrides take precedence over any conflicting value above.

- **colors.accent**: #00D97E
- **colors.primary**: #00D97E
