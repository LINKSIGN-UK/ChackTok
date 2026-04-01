# ChackTok Integration & Extensibility

ChackTok is designed as an extensible platform that integrates with event tech ecosystems, not as a standalone app.

## Integration Philosophy

ChackTok focuses on being a reliable workflow layer that connects:
- Commercial photo booth hardware
- Event capture and processing
- Guest delivery and sharing
- Business operations and management

Our integration approach prioritizes:
- Open compatibility over proprietary lock-in
- Standard protocols over custom implementations
- Data portability over data silos
- Partner enablement over closed ecosystems

---

## Current Integration Capabilities

### Hardware Integrations

#### Booth Control Layer
- **Bluetooth Device Control**
  - Direct communication with 12+ booth brands via Bluetooth LE
  - Standard control commands: rotation (speed/direction/duration)
  - Motion detection and automated triggering
  - Compatible with third-party Bluetooth control boxes
- **Supported protocols:**
  - Bluetooth 4.0+ (BLE)
  - Standard SPP (Serial Port Profile) where applicable
  - Manufacturer-specific protocols for certified brands
- **Integration path:**
  - Hardware partners can certify devices for ChackTok compatibility
  - Control specification available to licensed partners
  - Contact: support@chacktok.com

#### Camera Integration
- **GoPro Cameras (Official Support)**
  - GoPro HERO 9/10/11/12/13 via USB-C (wired) or WiFi (wireless)
  - Control: start/stop recording, settings adjustment, file transfer
  - Uses GoPro's public WiFi API and USB protocol
- **DSLR Cameras (Supported)**
  - Compatible with mainstream DSLR cameras for professional capture
  - Used in advanced event setups requiring higher image quality
- **Built-in Device Cameras**
  - Native iOS/Android camera APIs
  - Full resolution and capability access
  - Lens control, stabilization, filters

#### Peripheral Support
- **Printers**
  - WiFi photo printers via standard mobile printing protocols
  - iOS: AirPrint (native support)
  - Android: Mopria Print Service (native support)
  - Direct integration with select photo printer brands
- **External Displays**
  - HDMI displays (via adapter)
  - Wireless casting: AirPlay (iOS), Miracast (Android)
  - Smart TV built-in casting protocols
- **Remote Triggers**
  - Bluetooth remote shutter devices
  - Foot pedal triggers (BLE-compatible)
  - Booth control remotes (brand-specific)

### Software Integrations

#### Media Export & Portability
- **File Access**
  - All captured media stored in standard formats (MP4, JPG, PNG)
  - No proprietary encoding or watermark lock-in (for VIP users)
  - Full-resolution originals accessible via PC web console
  - Bulk download and archive operations supported
- **Export formats:**
  - Video: MP4 (H.264/H.265 codec)
  - Photo: JPG (high quality), PNG (overlays with transparency)
  - Metadata: EXIF data preserved where applicable
- **Storage locations:**
  - Cloud hosting: ChackTok cloud storage (included in subscription)
  - Local device: temporary cache for offline access
  - PC console: bulk download to local/network storage

#### Sharing & Delivery Integration
- **QR Code Sharing**
  - Standard QR codes (no app required for guest access)
  - Short-link generation for easy sharing
  - Public gallery URLs compatible with any browser
- **Social Platform Integration**
  - Direct sharing to Facebook, Instagram, WhatsApp (platform APIs)
  - Pre-formatted captions and hashtags
  - Optimized media formats for each platform
- **SMS/Email Delivery (where supported)**
  - Uses device native messaging capabilities
  - Third-party SMS gateway integration (for bulk sending)
  - Email delivery via standard SMTP protocols

#### PC Web Console
- **Access:** pc.chacktok.com
- **Capabilities:**
  - Event management and settings sync
  - Media library browsing and bulk operations
  - Background music upload and library management
  - User account and subscription management
- **Sync mechanism:**
  - Real-time sync between app and web console
  - Conflict resolution for concurrent edits
  - Offline changes queued and synced when online

---

## Planned Integration Features

### Q1-Q2 2026 Roadmap
- **Webhook Support (under development)**
  - Real-time event notifications for capture, upload, sharing
  - Configurable endpoints for third-party systems
  - Standard webhook payload format (JSON)
  - **Use cases:**
    - Trigger downstream workflows in event management systems
    - Sync media to external storage (Dropbox, Google Drive, S3)
    - Notify CRM systems of event completion
    - Update booking systems with event status
- **API Access (planned)**
  - RESTful API for event and media management
  - Authentication via API keys
  - Rate-limited access for partner applications
- **Third-Party Platform Integration (under evaluation)**
  - Event Management Platforms
  - CRM Systems (Salesforce, HubSpot, Zoho CRM)
  - Payment Gateways (Stripe, Square, PayPal)

---

## Integration Case Studies

### Example: Multi-Booth Fleet Management
- **Scenario:** Rental company operates 10+ booths across multiple events
- **Integration approach:**
  - All devices logged in with company account
  - Events managed centrally via PC web console
  - Templates shared across devices for brand consistency
  - Media automatically synced to cloud for client delivery
  - Post-event bulk export to company NAS storage
- **Result:** Centralized operations, consistent branding, streamlined delivery

---

## Partner Integration Program

### Hardware Partners
- **Benefits:**
  - Official certification and compatibility listing
  - Co-marketing opportunities
  - Early access to new ChackTok features
  - Technical integration support
- **Apply:** support@chacktok.com with subject "Hardware Partner Program"

### Software Integration Partners
- **Benefits:**
  - API access for integration development
  - Technical documentation and support
  - Partner listing in ChackTok ecosystem directory
  - Referral and revenue sharing opportunities
- **Target partners:**
  - Event management platforms
  - CRM and marketing automation systems
  - Cloud storage providers
  - Payment processors
- **Apply:** support@chacktok.com with subject "Software Integration Inquiry"

---

## Data Portability & Standards

### Open Data Formats
ChackTok commits to data portability:
- **Media files:** Standard MP4 (video), JPG/PNG (photos). No proprietary containers.
- **Event data:** Export event settings as JSON (planned).
- **User data:** Download all personal data via account settings. Account deletion removes all cloud data (GDPR/privacy compliance).

---

## Technical Resources

- **Documentation:**
  - [README — Platform Overview](README.md)
  - [HARDWARE_COMPATIBILITY — Detailed hardware tables](HARDWARE_COMPATIBILITY.md)
  - [FAQ — Technical questions](FAQ.md)
- **Support:**
  - Email: support@chacktok.com
  - Community: Facebook Group

---

**Document Version:** v2.0 (March 2026)  
**Last Updated:** 2026-03-31  
**Maintained by:** LINKSIGN UK CO., LTD  
*Roadmap subject to change based on partner demand and technical priorities.*
