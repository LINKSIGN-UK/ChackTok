# ChackTok Schema Templates

Last updated: 2026-07-07

Use these JSON-LD templates when importing the SEO page drafts into `www.chacktok.com`. Update `url`, `headline`, `description`, `dateModified`, and page-specific FAQ content for each page.

## Organization

```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "ChackTok",
  "url": "https://www.chacktok.com/",
  "sameAs": [
    "https://store.chacktok.com/",
    "https://www.youtube.com/@ChackTok",
    "https://www.instagram.com/chacktok/",
    "https://www.tiktok.com/@chacktok_app",
    "https://github.com/LINKSIGN-UK/ChackTok"
  ],
  "contactPoint": {
    "@type": "ContactPoint",
    "email": "support@chacktok.com",
    "contactType": "customer support"
  }
}
```

## SoftwareApplication

```json
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "ChackTok",
  "applicationCategory": "MultimediaApplication",
  "operatingSystem": "iOS, Android, Web",
  "description": "ChackTok is photo booth business software for event operators who need to create events, control supported booth hardware, capture branded media, and share photos or videos with guests.",
  "url": "https://www.chacktok.com/",
  "downloadUrl": [
    "https://apps.apple.com/us/app/chacktok-photo-booth-event/id1613120226",
    "https://play.google.com/store/apps/details?id=com.youfan.chacktok&hl=en_US&gl=US"
  ],
  "publisher": {
    "@type": "Organization",
    "name": "ChackTok"
  }
}
```

## FAQPage

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is ChackTok used for?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "ChackTok is used by photo booth operators to create event workflows, control supported booth hardware, capture photos and videos, apply branded assets, and share event media with guests."
      }
    },
    {
      "@type": "Question",
      "name": "Does ChackTok work with 360 photo booths?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "ChackTok supports 360 Photo Booth workflows where the booth, controller, mobile device, firmware, and app version are compatible. Operators should test the full setup before a commercial event."
      }
    }
  ]
}
```

## HowTo

```json
{
  "@context": "https://schema.org",
  "@type": "HowTo",
  "name": "How to set up a ChackTok photo booth event",
  "description": "A basic workflow for preparing a ChackTok event before guests arrive.",
  "step": [
    {
      "@type": "HowToStep",
      "name": "Install and log in",
      "text": "Install ChackTok from the official app store, log in, and confirm the account loads correctly."
    },
    {
      "@type": "HowToStep",
      "name": "Create an event",
      "text": "Create a new event or clone a reusable event template."
    },
    {
      "@type": "HowToStep",
      "name": "Connect supported hardware",
      "text": "Connect the supported booth, camera, display, or sharing setup and run a complete test."
    },
    {
      "@type": "HowToStep",
      "name": "Test sharing",
      "text": "Confirm QR code, gallery, email, SMS, or social sharing works on the event network where enabled."
    }
  ]
}
```

## BreadcrumbList

```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "https://www.chacktok.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Software",
      "item": "https://www.chacktok.com/software/"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "Photo Booth Software",
      "item": "https://www.chacktok.com/software/photo-booth-software/"
    }
  ]
}
```
