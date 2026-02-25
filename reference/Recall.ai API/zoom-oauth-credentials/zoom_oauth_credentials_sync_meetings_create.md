---
title: Manually Resync Meetings
excerpt: >-
  Manually re-sync meetings accessible from these credentials. This operation is
  asynchronous, and may take some time to complete.Use the `meeting_sync_status`
  field on the credential object to check status of sync.This is ONLY useful for
  debugging, and should not be called on a regular basis. Meetings are
  ordinarily automatically synced.


  The base rate limit for this endpoint is:

  - 300 requests per min per workspace
api:
  file: zoom-oauth-credentials.openapi_spec.yml
  operationId: zoom_oauth_credentials_sync_meetings_create
hidden: false
---