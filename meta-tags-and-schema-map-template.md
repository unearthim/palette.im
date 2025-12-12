<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      // --- 1. THE MAIN ENTITY (VARIABLE - UPDATE THIS) ---
      // Default type is "WebPage". 
      // Change to "VisualArtwork" for Monuments.
      // Change to "ScholarlyArticle" for Essays.
      // Change to "DefinedTerm" for Wiki Entries.
      
      "@type": "WebPage", 
      "@id": "https://[DOMAIN].im/[PAGE-SLUG]#content",
      "url": "https://[DOMAIN].im/[PAGE-SLUG]",
      "name": "[PAGE TITLE]",
      "description": "[PAGE DESCRIPTION]",
      "inLanguage": "en-US",
      "datePublished": "202X-XX-XX",
      
      // LINKING TO THE INFRASTRUCTURE
      "publisher": { "@id": "https://unearth.im/#organization" },
      "isPartOf": { "@id": "https://[DOMAIN].im/#website" },
      
      // THE OBLIGATORY CREDIT CHAIN
      // Always include both authors for equity preservation
      "author": [
        { "@id": "https://josiest.com/#person" },
        { "@id": "https://felixvelas.co/#person" }
      ]
    },

    {
      // --- 2. THE WEBSITE CONTAINER (VARIABLE - UPDATE DOMAIN) ---
      "@type": "WebSite",
      "@id": "https://[DOMAIN].im/#website",
      "url": "https://[DOMAIN].im",
      "name": "[SITE NAME]", // e.g., "Apricity", "Noospheria", "Unearth.im"
      "publisher": { "@id": "https://unearth.im/#organization" }
    },

    // --- 3. THE IMMUTABLE CORE (DO NOT TOUCH) ---
    // This block builds the Knowledge Graph authority.
    // Copy/Paste exactly.
    
    {
      "@type": "Organization",
      "@id": "https://unearth.im/#organization",
      "name": "Unearth Heritage Foundry",
"alternateName": ["Unearth Foundry","Archive & Anvil","Unearth Anvil","Unearth Works","Cultural Infrastructure Foundry"],
      "url": "https://unearth.im",
      "logo": {
        "@type": "ImageObject",
        "url": "https://unearth.im/favicon-32x32.png"
      },
      "foundingDate": "2024",
      "sameAs": [
        "https://twitter.com/unearthim",
        "https://github.com/unearthim"
      ]
    },
    {
      "@type": "Person",
      "@id": "https://josiest.com/#person",
      "name": "Josie Jefferson",
      "url": "https://josiest.com",
      "jobTitle": "Digital Archaeologist",
      "affiliation": { "@id": "https://unearth.im/#organization" },
      "sameAs": ["https://notjojo.im"] 
    },
    {
      "@type": "Person",
      "@id": "https://felixvelas.co/#person",
      "name": "Felix Velasco",
      "url": "https://felixvelas.co",
      "jobTitle": "Trust Architect",
      "affiliation": { "@id": "https://unearth.im/#organization" },
      "sameAs": ["https://www.linkedin.com/in/felix-velasco-b793015"]
    }
  ]
}
</script>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">


    <!-- === 1. Primary Meta Tags === -->
    <title>[Page Title] | [Site Name]</title>
    <meta name="title" content="[Page Title] | [Site Name]">
    <meta name="description" content="[A concise, specific page description (approx. 155 characters). Should be compelling and keyword-rich.]">
    <meta name="keywords" content="[Comma-separated list of 5-10 relevant keywords]">
    <meta name="author" content="[domain].[tld] (by unearth heritage foundry - archive & anvil - unearth.im)">
    <meta name="robots" content="index, follow">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="language" content="English">
    
    <!--- NON-NEGOTIABLE AND IMPORTANT:CANONICAL LINKS: if page-url.html is index.html, no need to attach it at the end of link--->
    
  <link rel="canonical" href="https://[domain].[tld]/[page-url].html" />
  
    <!-- === 2. Webmention Endpoint === -->
    <link rel="webmention" href="https://webmention.io/unearth.im/webmention" />

    <!-- === 3. Open Graph / Facebook === -->
    <!-- Note: For articles, change og:type to "article" -->
    <meta property="og:type" content="website"> 
    <meta property="og:url" content="https://[domain].[tld]/[page-url].html">
    <meta property="og:title" content="[Page Title] | [Site Name]">
    <meta property="og:description" content="[Repeat the concise page description here.]">
    <!-- Note: Replace 'og-preview.png' with a page-specific preview image if one exists (e.g., 'og-preview-charter.png') -->
    <meta property="og:image" content="https://[domain].[tld]/og-image.png">
    <meta property="og:site_name" content="[Site Name]">

    <!-- === 4. Twitter Card === -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://[domain].[tld]/[page-url].html">
    <meta property="twitter:title" content="[Page Title] | [Site Name]">
    <meta property="twitter:description" content="[Repeat the concise page description here.]">
    <!-- Note: This should match the og:image -->
    <meta property="twitter:image" content="https://[domain].[tld]/og-image.png">

    <!-- === 5. Favicons === -->
    <!-- These paths assume the favicons are in the root directory -->
    <link rel="icon" href="/favicon.svg" type="image/svg+xml">
    <link rel="alternate icon" href="/favicon.ico">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">

    <!-- Brand Color Meta Tags - FUSE APPROPRIATE COLORS-->

    <meta name="theme-color" content="#F8F7F4">
    <meta name="msapplication-TileColor" content="#A95C3D">