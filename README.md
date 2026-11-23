# Oscar Medina | GIS & Data Engineering

I work at the intersection of GIS, data engineering, and urban redevelopment. My work helps teams see where services are being delivered, keep property information current, and make operational maps easier to maintain.

## Selected work

| Project | What the team needed | What the work enabled |
| --- | --- | --- |
| [Land care field reporting](#land-care-field-reporting) | A consistent view of maintenance assignments and field activity | Map-based review of assigned work and submitted observations across reporting periods |
| [Parcel assessment reconciliation](#parcel-assessment-reconciliation) | A reviewable way to refresh property attributes | A proposed change set that staff can inspect before applying updates, with a record of the results |
| [Property data publishing](#property-data-publishing) | A dependable refresh process for a hosted property layer | A repeatable way to publish, check, and recover a layer used by web maps |

## Land care field reporting

**Challenge.** Field submissions document where crews reported work. Program staff also need to see which parcels were assigned and how activity changes from one reporting period to the next.

**Approach.** The workflow turns survey submissions into map-ready records and maintains views for current activity and historical review. Assignments and submissions can be compared by parcel and reporting period.

**Result.** Staff can start with the active reporting period and use the historical view to look back at earlier activity. The shared views give field reporting and program monitoring a consistent geographic reference.

**Skills demonstrated:** Spatial data integration, survey data quality, hosted feature layers, operational reporting.

## Parcel assessment reconciliation

**Challenge.** An assessment refresh can include incomplete records and ambiguous parcel matches. Applying changes in bulk makes it harder to review exceptions and trace what happened to a record.

**Approach.** The workflow previews proposed updates and surfaces ambiguous matches for review. It preserves existing values when incoming values are blank and records the results of applied changes.

**Result.** Staff can review the proposed updates before they are applied and use the audit trail to follow up on exceptions.

**Skills demonstrated:** Record reconciliation, data validation, bulk update controls, auditability.

## Property data publishing

**Challenge.** A hosted property layer needs to stay current because web maps depend on it. A refresh process also needs a way to verify the result and recover when publishing fails.

**Approach.** The workflow prepares a property snapshot for publication, checks the hosted result, and includes a documented recovery procedure.

**Result.** Routine refreshes and recovery follow a repeatable process. Staff have a way to check the published layer before relying on it in a map.

**Skills demonstrated:** Geospatial ETL, hosted data publishing, validation, operational recovery.

## Toolkit

Python · SQL · PostgreSQL/PostGIS · ArcGIS Online

These case studies describe team projects at a high level. They focus on the operational problems, the broad approaches, and what the resulting workflows support.
