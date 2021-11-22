## Mezzanotte Labs, LLC.

## Who we are
We are actively-employed security professionals, who are security hobbyists in our spare time.
We have an average of 10 years of past direct experience and achievements including but not limited to:
   - Senior incident response and analytical roles in multiple Fortune 100 SOCs
   - Senior/Principal level security engineering roles in Software and Financial sectors
   - Senior/Principal level developer roles in Software startup companies
   - Security-related industry certifications such as GPEN, OSCP, OSCE, CEH, CCNA, Security+, Linux+
   - Making antivirus sales reps eat their own words :)

## Abstract
In our professional careers we have rigorously evaluated dozens of name brand security products. These products
range from antivirus, EDR, SIEM, IDS/IPS, and DLP, and range anywhere from tens to hundreds of thousands of dollars
in cost (sometimes more for larger companies).  A trend worth noting is that this wide variety of different tools
is coming from a smaller and smaller pool of companies, as larger players consume their competitors and thus absorb
their products; This presents some problems:

1. **Vendor lock-in**
```
    a. Consolidation of services is good, but not when it comes with a price tag that says "we know you need us".
    b. Tool overlap, and lack of integration abilities
        1a. Example: Lots of "next-gen" AV products are focusing on behavioral/heuristic detection capabilities
            (as they should).  However, in order to detect such activity, they need to collect more granular datasets
            from the endpoint. This in essence has resulted in massive overlap between AV and EDR solutions, and
            has given companies the option to A. pay for both EDR and AV to collect the same exact data, or B. remove
            their old EDR solutions (which historically have better support more SIEM integrations, more open source
            options, and far less-buggy/impacting deployments), and succumb to the vendor lock-in.
        1b. Example: Lack of integration ability is another vendor lock-in coercion tactic (whether they knowingly
            do this or not, it is). We have been on sales calls with three of the top four players in the next-gen
            AV space and asked how we can send the data that they collect to our own SIEM, their reply was unanimously
            something akin to "We currently don't support that option, but that would be a lot of data anywas, you don't
            want to collect all that ... we do however offer our own SIEM product that you might be interested in,
            let me send you a quote for that".  This new norm of vendors collecting your data and holding it hostage
            within their own cloud (while often times charging a premium to accesss it by throttling/limiting API
            requests) is nothing short of extortion. While this may be ok with some organizations, this presents serious
            problems for matured security programs that already have a significant amount invested into their on-prem
            tooling, or have the need to monitor assets residing in air-gapped environments. In summation, the whole
            "its us or them" approach detracts from the "single pane of glass" ideal that security departments strive
            to create.
        1c: Example: CASB overlap with modern firewalls
```
2. **Dilution of quality and expertise**
```
    a. As companies expand their horizons, they knowingly stray slightly farther from their own "bread and butter".
       This has worked well in some cases, not-so-well in others (not to mention names, but Mand***t is guilty of this)
```
3. **Loss of functionality**
```
    a. A trend observed while evaluating products has been that vendors want to sell you subscription-based services.
       This in itself is not problematic, however it is problematic and unethical when they coerce customers into
       using subscription based services (SaaS vs. on-prem) by offering either no non-hosted alernatives, or offering
       non-hosted alternatives that lack the same functionality as their cloud-hosted counterparts.
    b. As mentioned above, from our anecdotal experience evaluating products it seems that vendors might purposely be
       dumbing down their abilities to integrate with other tools if the tool in question is a competitor to anything
       within their own product suite; I can't blame them for this, but it doesn't make the customer's life any easier.
```
In addition to the problems presented by an ever-shrinking pool of ever-larger software giants, one thing definitely
worth noting is *how simple* some of these products are once you strip away the fancy UI. The truth is most things
really are *that* simple, but often times this fact is lost deep beneath the flashy UI's, and marketed as "secret sauce"
to less-savvy consumers.  We can accurately state that a lot of security products accomplish their bidding by
hilariously basic means (we would not make this assertion had we not reverse-engineered a number of "cutting-edge"
security products that shall remain nameless. **We also might not have reverse engineered anything because that could
be illegal**).

With a firm-grip on the pulse of cyber security software trends, we at Mezzanotte Labs plan to disrupt the industry in a
way that benefits consumers by offering an OS, cloud/non-cloud agnostic product suite that that can easily be integrated
with any existing tooling in any type of environment.  Our suite consists of tools catered to both red and blue teams,
with the tools themselves ranging everywhere from the more mundane yet necessary security tools that every team needs,
to the bleeding edge specialized exciting niche products that will tackle unqiue problems in new ways.

The ideas for each product within our product suite are derived directly from real-world use-cases, and in many cases
the products are (greatly enhanced) variants of solutions that we have personally architected, developed, and
implemeneted in the past at various organizations.
