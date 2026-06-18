# Enatega Multi-vendor Alignment to Maroon Market

This repository (`onitas-market`) has been structurally aligned with the **Maroon Ecosystem**. 

## 1. Kernel Integration
The universal Maroon Design System has been mounted as a Git submodule at `/packages/maroon-kernel`.
- **Location:** `packages/maroon-kernel/`
- **Usage:** Both `enatega-multivendor-web` and `enatega-multivendor-admin` should import their CSS tokens and Qwik primitives directly from this unified kernel to ensure visual consistency across the entire Maroon ecosystem.

## 2. Intelligence API Routing
In Phase 3 of the ecosystem rollout, the default GraphQL backend of Enatega will be deprecated in favor of the unified **Maroon Intelligence API** (hosted in `Maroon-Market`). 

### Next Steps for Frontend Alignment:
- Replace `GRAPHQL_URL` references in the React Native and Web environments with the Maroon Intelligence API endpoint.
- Adopt the `product_categories.okf.md` schema for all vendor product definitions instead of localized SQL structures.
