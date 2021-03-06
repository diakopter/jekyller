---

layout: default

style: |

    #Cover h2 {
        margin:65px 0 0;
        color:#FFF;
        text-align:center;
        font-size:70px;
        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        color:#FFF;
        font-style:italic;
        font-size:20px;
        }
        #Cover p a {
            color:#FFF;
            }
    #Picture h2 {
        color:#FFF;
        }
    #SeeMore h2 {
        font-size:100px
        }
    #SeeMore img {
        width:0.72em;
        height:0.72em;
        }
---

# Who is this and what have you done with my CPAN {#Cover}

![](pictures/cover.jpg)
<!-- photo by John Carey, fiftyfootshadows.net -->


## Does size matter?

- sheer magnitude
- growth rate
- ...Yes, it matters because of what it represents, which are important to measure when planning marketing and advocacy activities and policies
    1. ...mindshare/userbase
    2. ...inertia
    3. ...which feed into each other, naturally


## Who Has a "CPAN"?

* ...Typical: "there ain’t no CPAN for Python" "..Ruby" "..JavaScript" - blogs.perl.org - Jan 2012
* ...But why mention those languages?
* ...Why not Java and the innumerable other JVM language ports/implementations that have access to all the same libraries?
* ...Why not the Microsoft languages and the umpteen languages on .NET (CLR/mono)?


## Not just size matters

- Recency of releases.  (let's pick 3 years).  If a distribution has a release in the last three years, then probably at least one of these is true:
    1. The problem space is recent
    2. The maintainer is adding new features or keeping up with bug reports and bitrot
    3. Not-Invented-Here duplication
- ...Language Archive Matchup Game

## Observations:

1. ...Junk level on RubyGems and PyPi is extremely high
2. ...Hackage tends toward precise "known" algorithms and standardized protocol implementation, emphasizes co-composability - "one or two best [only] ways to do everything"
3. ...node's npm tends toward language and orientation/paradigm tweaking - DSLs and JS dialects as well as paradigm-importing combinators and shortcuts


## Observations:

4. ...Maven's Central Repo STRONGLY tends toward enterprise software and interopability plugins
5. ...NuGet tends toward library bindings and components/plugins of existing componentized/pluggable software systems
6. ...Packagist is currently too small and growing too slowly to matter.  ...(Can you make abstractions and design for modularity in PHP?)
7. ...CPAN is a mix of all of the above.

## Conclusions:

- ...When advocating Perl, don't emphasize the scope of problem spaces that CPAN covers
    - ...npm and maven are far bigger (e.g. 309 mongodb vs 31)
    - ...(and more importantly, growing far more quickly)
- ...Qualify your love for CPAN by specifying the specific distinctives you appreciate
    1. ...CPANTesters network and platform support matrix
    2. ...(optional) integrated bug tracking and communication with author

## Conclusions:

- Qualify your love for CPAN by specifying the specific distinctives you appreciate
    3. ...ability to take over namespaces of dead or just unmaintained stuff
    4. ...awesome documentation a cultural standard
    5. ...runs the integrated test suite upon install

## Conclusions:

- Qualify your love for CPAN by specifying the specific distinctives you appreciate
    6. ...pretty good searching
    7. ...very mature authentication, upload, and permission management system, with namespace claiming/approval
    8. ...distribution ratings/reviews


