# Feature catalogue

Snapshot: 15 October 2026. This is a product inventory, not a claim that every implemented flow is enabled or production-ready.

**Demonstrated** means the interface was inspected in the local application for this showcase. **Implemented** means a corresponding private application surface exists; operation in a deployed environment still requires verification. **Deferred** means outside the initial launch commitment, including features with existing code.

## Public presence and client experience

| Capability | Purpose and scope | Status |
| --- | --- | --- |
| Provider page | Branded identity, introduction, imagery, experience and calls to action | Demonstrated on coaching and fitness profiles |
| Visual customisation | Different themes, colours, typography and page treatments | Different public treatments demonstrated; editor implementation inspected |
| Service catalogue | Names, descriptions, prices, durations, delivery methods and service categories | Demonstrated |
| Free and paid offers | Discovery calls alongside priced appointments | Display demonstrated; paid processing is separate |
| Service benefits and preparation | Explain the session and what the client should expect | Demonstrated in coaching catalogue |
| Testimonials and case studies | Provider-managed supporting content | Demo content rendered; examples are fictional |
| FAQs | Expandable questions and search interface | Expansion demonstrated |
| Responsive layouts | Public profiles, catalogue and booking interface on desktop and mobile | Demonstrated at 1280 × 720 and 390 × 844 |
| Booking service selection | Choose an offer within the provider page | Demonstrated |
| Date/time selection | Display available slots and the displayed timezone | Demonstrated for a future coaching date |
| Client details | Name, email, optional phone and notes | Form demonstrated, left empty |
| Payment and confirmation | Progress from booking details to the configured payment/confirmation path | Implemented; no checkout or booking submitted during this showcase |
| Booking access | Client access to booking information and receipts | Implemented; not freshly demonstrated here |
| Cancellation and rescheduling | Manage appointment changes under the provider's policy | Implemented; policy consistency and failure paths remain release checks |

## Provider workspace

| Capability | Purpose and scope | Status |
| --- | --- | --- |
| Signup and onboarding | Establish provider identity, business information and the first service | Implemented; service-step captures included from prior development |
| Page editor | Edit profile, page content, services and visual presentation with a preview | Implemented; source surface inspected |
| Service management | Create and edit service offers, prices and durations | Implemented; published output demonstrated |
| Availability | Define the times clients can request | Implemented; resulting public slots demonstrated |
| Calendar | Day/week/month appointment views and service colours | Implemented; a prior synthetic-data component capture is included |
| Booking management | Upcoming/past appointments and booking actions | Implemented; authenticated workspace not recaptured here |
| Client management | Provider client records and associated booking context | Implemented; no real client data included |
| Payments | Connect onboarding, transaction/payout-related surfaces and payment status | Implemented; live processing/payout verification not claimed |
| Account and business settings | Profile, business, booking rules, notifications, security and billing settings | Implemented; not all settings individually verified here |
| Transactional communication | Booking/payment emails and background work | Implemented; delivery is environment-dependent |
| Free/Pro subscription model | Provider entitlements and billing surfaces | Implemented direction; prices/limits are not promised in this showcase |

## Wider product surface

| Area | Intended value | Launch treatment |
| --- | --- | --- |
| Google Calendar and Zoom | Reduce scheduling/video handoffs | Deferred; reviewed feature switches are disabled |
| Advanced analytics | Summarise provider business performance | Optional/flagged; not a launch guarantee |
| Packages and programmes | Sell and track multi-session offers | Deferred/flagged; a sample package description does not establish working package fulfilment |
| SEO tools | Support provider discoverability | Optional/flagged; outside the core launch slice |
| Session journal | Organise session notes and follow-ups | Optional/flagged; requires separate privacy and workflow validation |
| AI-assisted features | Help with selected content or provider workflows | Deferred; not represented as a current general capability |
| Waitlists and growth extras | Support later engagement and distribution experiments | Deferred; demand should determine scope |

A menu item, prototype screen or API implementation alone does not establish that a feature works end to end. Current feature switches and release decisions take precedence over older marketing screenshots.
