# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: ui/landing-navigation.spec.ts >> Landing public UI navigation >> footer links reach each destination
- Location: tests/ui/landing-navigation.spec.ts:115:7

# Error details

```
Test timeout of 60000ms exceeded.
```

# Page snapshot

```yaml
- generic [ref=e3]:
  - generic [ref=e5]:
    - generic [ref=e7]:
      - generic [ref=e8]:
        - button "Go to home page" [ref=e9] [cursor=pointer]:
          - img "SkulApp Logo" [ref=e10]
        - navigation "Primary" [ref=e11]:
          - list [ref=e12]:
            - listitem [ref=e13]:
              - button "Home" [ref=e14] [cursor=pointer]
            - listitem [ref=e15]:
              - button "Features" [ref=e16] [cursor=pointer]
            - listitem [ref=e17]:
              - button "How it Works" [ref=e18] [cursor=pointer]
            - listitem [ref=e19]:
              - button "Pricing" [ref=e20] [cursor=pointer]
            - listitem [ref=e21]:
              - button "Support" [ref=e22] [cursor=pointer]
            - listitem [ref=e23]:
              - button "About" [ref=e24] [cursor=pointer]
        - generic [ref=e25]:
          - button "Contact" [ref=e26] [cursor=pointer]
          - button "Account Login" [ref=e27] [cursor=pointer]:
            - img [ref=e28]
            - text: Account Login
      - generic [ref=e31]: "Breakpoint: desktop"
    - generic [ref=e32]:
      - paragraph [ref=e33]: SkulApp
      - heading "Terms & Conditions" [level=1] [ref=e34]
      - paragraph [ref=e35]: The basic service terms for schools and users working with SkulApp.
  - main [ref=e36]:
    - generic [ref=e37]:
      - generic [ref=e38]:
        - heading "Service Use" [level=2] [ref=e39]
        - paragraph [ref=e40]: SkulApp provides digital tools for school management, communication, admissions, billing, and learning support.
      - generic [ref=e41]:
        - heading "Availability" [level=2] [ref=e42]
        - paragraph [ref=e43]: We aim to keep the platform reliable while continuing to improve features, security, and performance.
      - generic [ref=e44]:
        - heading "Support" [level=2] [ref=e45]
        - paragraph [ref=e46]: Schools can contact SkulApp support for onboarding, platform questions, and service guidance.
  - contentinfo [ref=e47]:
    - generic [ref=e49]:
      - generic [ref=e50]:
        - generic [ref=e51]:
          - heading "Links" [level=3] [ref=e52]
          - list [ref=e53]:
            - listitem [ref=e54]:
              - link "Home" [ref=e55] [cursor=pointer]:
                - /url: /
            - listitem [ref=e56]:
              - link "Features" [ref=e57] [cursor=pointer]:
                - /url: /#features
            - listitem [ref=e58]:
              - link "Pricing" [ref=e59] [cursor=pointer]:
                - /url: /plans
            - listitem [ref=e60]:
              - link "Support" [ref=e61] [cursor=pointer]:
                - /url: /faq
            - listitem [ref=e62]:
              - link "Register School" [ref=e63] [cursor=pointer]:
                - /url: /registration/school-info
            - listitem [ref=e64]:
              - link "Explore Schools" [ref=e65] [cursor=pointer]:
                - /url: /testimonials
        - generic [ref=e66]:
          - heading "Platform Tools" [level=3] [ref=e67]
          - generic [ref=e68]:
            - generic [ref=e69]: Teacher Dashboard
            - generic [ref=e70]: Student Dashboard
            - generic [ref=e71]: Parent Dashboard
            - generic [ref=e72]: Admin Tools
            - generic [ref=e73]: Digital Library
            - generic [ref=e74]: Terminal Reports
        - generic [ref=e75]:
          - generic [ref=e76]:
            - heading "Hours" [level=3] [ref=e77]
            - paragraph [ref=e78]:
              - text: "Mon - Sat ( 07 : 00 - 16 : 00 )"
              - text: Closed on Sunday
          - generic [ref=e79]:
            - heading "Address" [level=3] [ref=e80]
            - generic [ref=e81]:
              - paragraph [ref=e82]:
                - text: SkulApp Headquarters
                - text: 12 Education Crescent, Accra, Ghana
              - button "See on maps" [ref=e83] [cursor=pointer]
        - generic [ref=e84]:
          - generic [ref=e85]:
            - img "SkulApp Logo" [ref=e86]
            - paragraph [ref=e87]: A smarter way to manage, teach, and learn.
          - generic [ref=e88]:
            - generic [ref=e89]:
              - generic [ref=e90]:
                - img "Phone" [ref=e91]
                - generic [ref=e92]: ( + 555 ) 123 - 4567
              - generic [ref=e93]:
                - img "Email" [ref=e94]
                - generic [ref=e95]: info@skulapp.com
            - button "Back to top" [ref=e96] [cursor=pointer]:
              - img "Back to top" [ref=e97]
      - generic [ref=e98]:
        - paragraph [ref=e99]: © SkulApp, 2025. All rights reserved.
        - generic [ref=e100]:
          - link "Privacy Policy" [ref=e101] [cursor=pointer]:
            - /url: /privacy
          - link "User Policy" [ref=e102] [cursor=pointer]:
            - /url: /user-policy
          - link "Terms & Conditions" [ref=e103] [cursor=pointer]:
            - /url: /terms
```