---
title: Accept
description: 'This pattern is used to acknowledge and accept a request (`Offer`). This should be interpreted to mean that the `target` intends to act on the request in some way. It does not imply any kind of outcome beyond this.'
date: "2021-03-08"
type: patterns
event_notifications_pattern: []
pattern_category: acknowledgements
payload:
  id: "urn:uuid:4fb3af44-d4f8-4226-9475-2d09c2d8d9e0"
  type: "Accept"
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

