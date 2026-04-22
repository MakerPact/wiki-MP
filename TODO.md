# TODO

- [ ] Implement custom anchor IDs using `{#anchor}` syntax if needed
- [ ] Add tests for anchor link navigation
- [ ] Add voltage dividers page with cross-link to FAQ #5
## labsupplys.md :
- [x] Standardize product entry format with tier indicators
- [x] Add tier indicators: MUST (⭐), NICE (✨), LUXURY (💎)
- [x] Organize entries by price (lowest to highest) within each section
- [x] Update all sections with proper labels and consistent formatting
- [ ] Include links to product pages or tutorials. crosslink entire site.
- [ ] Add safety and PPE guidelines.
## combiningsketches.md :
- [ ] Incomplete Sentences need to be fixed.
- [ ] Vague References:
  - "In some cases, the library file name may be in quotes, but this is a special case. In the case the library file is not in the normal location..." — Repetitive and unclear. Consolidate into one explanation.
- [ ] Inconsistent Formatting

  - The note "Pay Attention" appears twice with different styling expectations but no visual distinction.
- [ ] Add a summary checklist at the end:

    Copy library includes
    Copy definitions (check for name conflicts)
    Copy global variables (check for name conflicts)
    Copy Setup contents (not the declaration)
    Copy Loop contents (not the declaration)
    Verify the combined sketch compiles

## millisvsdelay.md :
- [x] Fix vague phrasing — "millis() is a counter that 'evolves by a clock'" is awkward. Better: "millis() is a counter driven by the system clock" or "millis() is a counter that increments with time."
- [x] Add code example showing millis() in practice (the page mentions BlinkWithoutDelay.ino but doesn't show it)
- [x] Clarify the overflow behavior of millis() (it resets after ~50 days)
- [x] Explain why delay() blocks interrupts (important for real applications)
## breadboards.md :
- [ ] Add a code example showing millis() in practice (the page mentions BlinkWithoutDelay.ino but doesn't show it)
- [ ] Clarify the overflow behavior of millis() (it resets after ~50 days)
- [ ] Explain why delay() blocks interrupts (important for real applications) this is located near Build the Circuit heading.
  
## resistors.md :

- [ ] Add a warning about exceeding forward voltage (reverse polarity can destroy an LED instantly).

  Mention resistor tolerances — standard resistors come in specific values (E12 or E24 series), so "next size larger" needs context.
  
  Add a visual circuit diagram showing correct LED polarity (longer leg = positive).

## multimeter.md :

- [ ] Weak opening — "A multimeter is an essential tool for anyone working with electronics" is generic. Consider adding what makes it essential (e.g., "for diagnosing circuits, testing connections, and troubleshooting electrical problems").
- [ ] Continuity explanation could be clearer — Consider: "If the multimeter beeps, the connection is complete (low resistance). If it doesn't beep, there's a break in the circuit."

## ninevolts.md :

- [ ] Clarify that the 7-hour estimate is theoretical and that real-world runtime is much shorter due to voltage drop.
- [ ] Explain why 9V batteries are inefficient: they're designed for high-impedance devices (smoke detectors, guitar pedals), not for circuits needing sustained current draw.
- [ ] Suggest better alternatives (AA/AAA batteries in series, lithium-ion packs, or USB power).

## logiclevelshifter.md :
- [x] Remove duplicate home link and duplicate images

## Cross link all of the markdown files that have overlapping topics.
