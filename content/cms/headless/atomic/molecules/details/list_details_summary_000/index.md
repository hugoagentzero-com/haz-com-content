---
title: FAQ list (headless demo)
# Bundle props land on page.Params.props (do not nest under params: — that becomes Params.params).
props:
  collection:
    - key: headless_what
      enabled: true
      summary: What is a headless CMS source here?
      details: "<p>This row comes from a Hugo headless bundle under <code>content/cms/headless/…</code> — same molecule, <code>provider: headless</code>.</p>"
    - key: headless_stack
      enabled: true
      summary: Why do these sit under the same list wrapper?
      details: "<p>Layouts stacks two list instances in a multiplier. Each emits bare <code>&lt;details&gt;</code> rows; the FE sees one stack.</p>"
      open: true
---
