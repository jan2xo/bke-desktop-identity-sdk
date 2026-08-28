# BKE Desktop Identity SDK

STATUS: SCAFFOLD / PRE-API

## Purpose

BKE.Desktop.Identity is the planned reusable .NET client foundation for installation identity, product manifest loading, manifest schema validation, and product-context validation mechanics across supported desktop platforms.

This 0.1.0 repository is scaffold-only. It intentionally does not define a public identity API or implement product behavior.

## Boundaries

The package will provide reusable integration mechanics when those contracts are derived from certified BKE products and evidence review. It does not own licensing authority, entitlement decisions, license verification authority, trusted policy, privileged execution, or product-specific business rules. The Licensing Agent remains the local authority where applicable.

No Air Stack or Render Dock implementation is copied, and no product identifiers are hardcoded.

## Status and versioning

The public API is intentionally not frozen. Implementation will be extracted later from certified working BKE products after protocol and behavior evidence is reviewed. Package versions are explicit and follow semantic versioning. No package feed or production publication is implied by this repository.

## Development

The project targets .NET 8 (net8.0). Restore, build, test, and package validation are performed in GitHub Actions. The package is currently a CI artifact candidate only.
