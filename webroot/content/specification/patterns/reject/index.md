---
title: Reject
description: 'This pattern is used to acknowledge and reject a request (`Offer`). This should be interpreted to mean that the `target` will take no further action with regard to this `Offer`. It does not imply any kind of outcome beyond this.'
date: "2021-03-08"
type: patterns
event_notifications_pattern: []
pattern_category: acknowledgements
payload:
  id: "urn:uuid:668f26e0-2c8d-4117-a0d2-ee713523bcb1"
  type: "Reject"
#  actor:
#    lookup: "generic-service"
  origin:
    lookup: "generic-service"
  target:
    lookup: "generic-organisation"
#  object:
#    lookup: "offer"
#  context:
#    lookup: "offer-for-context"
  inReplyTo:
    lookup: "required-inReplyTo"
---

