---
layout: default
title: F# Core Engineering Activities
---

<br />

The "F# Core Engineering Group" is a loose term for the people who maintain and contribute to the repositories of [The F# Software Foundation](http://fsharp.org). There are no "meetings", all work is coordinated via github issues.

These people - both maintainers and contributors - work cooperatively with major industrial and community contributors to F# to facilitate open-source contributions to the F# core components. For example:

* They together run the [F# Language Design and Core Library RFC Process](http://fsharp.github.io/2016/09/26/fsharp-rfc-process.html)

* They together help maintain the "Use F#" guides such as [Use F# on Windows](http://fsharp.org/use/windows), [Use F# on Linux](http://fsharp.org/use/linux) and [Use F# on OSX](http://fsharp.org/use/mac).

* They together work cooperatively with the [Visual F# Tools team](http://blogs.msdn.com/b/fsharpteam) to 
  [facilitate contributions](http://fsharp.github.io/2014/06/18/fsharp-contributions.html) to
  the F# language, compiler and libraries via the [Visual F# Tools repository](https://github.com/Microsoft/visualfsharp)

* They together cooperate with the [Xamarin](http://xamarin.com) team to see F# packaged as part of Xamarin tools for [OSX](http://fsharp.org/use/mac), 
  [Android](http://fsharp.org/use/android) and [iOS](http://fsharp.org/use/ios).

* They together cooperate with the [Mono team](http://www.mono-project.com/) to see F# packaged as part of standard Mono distributions.

* They together cooperate with the [Debian packaging team](http://packages.qa.debian.org/f/fsharp.html) to see F# packaged on Debian.

The [vim-fsharp](https://github.com/fsharp/vim-fsharp), [emacs-mode-fsharp](https://github.com/fsharp/emacs-fsharp-mode), [sublime-fsharp-package](https://github.com/fsharp) and [FAKE](http://github.com/fsharp/FAKE) repositories are here for historical reasons, they are not considered to be FSSF repositories.

Please join in the fun!


## Goals and Remit

See  our [Goals and Remit](http://fsharp.github.io/2013/07/09/group-remit.html) document.

The group dates back to 2013 and the FSSF board assigns permissions and conducts oversight of the activities [through a board resolution in 2015](http://foundation.fsharp.org/core_engineering_wg).  

The FSSF board appoint a "chairperson" who has responsibility for assigning permissions and arranging a degree of oversight. The last chairperson appointed was Tomas Petricek for 2015-16, a new chaiperson is currently being sought.

Maintainer (pull-request) permissions for various repositories is listed below.

##  Group Membership

The "group" is just a name given to contributors to repositories such as [visualfsharp](http://github.com/Microsoft/visualfsharp),  [fsharp](http://github.com/fsharp/fsharp), [FSharp.Compiler.Service](http://github.com/fsharp/FSharp.Compiler.Service), [FSharpLangDesign](http://github.com/fsharp/FSharpLangDesign) and this site, [fsharp.github.io](http://github.com/fsharp/fsharp.github.io).  

Some specific people with maintainer permissions are as follows:

* [**fsharp**](http://github.com/fsharp/fsharp) - [Don Syme](https://github.com/dsyme/), Enrico Sada, Tomas Petricek  and http://github.com/fsharp/FSharp.Compiler.Service
* [**FSharp.Compiler.Service**](http://github.com/fsharp/FSharp.Compiler.Service) [Don Syme](https://github.com/dsyme/), Enrico Sada, Tomas Petricek
* [**fsharp.github.io**](http://github.com/fsharp/fsharp.github.io) - [Don Syme](https://github.com/dsyme/), Dave Thomas, Tomas Petricek  and http://github.com/fsharp/FSharp.Compiler.Service
* [**fslang-design**](http://github.com/fsharp/fslang-design) and [**fslang-suggestions**](http://github.com/fsharp/fslang-suggestions) -  [Don Syme](https://github.com/dsyme/), [Chester Husk III](https://github.com/baronfel/), [Jared Hester](https://github.com/cloudRoutine), [Kurt Schelfthout](https://github.com/kurtschelfthout), [Marcus Griep](https://github.com/neoeinstein) - Language Design, Suggestion, RFC Curation and other contributions

## Get Involved 


To get involved:

* [Contribute to the F# compiler and core library](http://fsharp.github.io/2014/06/18/fsharp-contributions.html)

* [Contribute to the F# RFC process](http://fsharp.github.io/2016/09/26/fsharp-rfc-process.html)

* [Contribute to guides and blog entries on this site](https://github.com/fsharp/fsharp.github.io/tree/master/_posts)

* [Contribute to guides on fsharp.org](https://github.com/fsharp/fsfoundation/tree/gh-pages/guides)

* [Contribute to other core repositories](http://github.com/fsharp) and [F# community incubation projects](http://github.com/fsprojects)

Our mission is to maintain the excellent quality of the core F# implementation across these platforms,
and to extend the set of tools available for F# across your favorite platforms.

If you are working in some particular area and would like to update your activity/responsibility, please [submit an edit to this page](https://github.com/fsharp/fsharp.github.io/edit/master/index.md).

<a id="bloglist" > &nbsp; </a>
<br />

## Guides and Posts


<div>
{% for post in site.posts %}

    <br />
    <h2>
      <a href="{{ site.baseurl }}{{ post.url }}">
        {{ post.title }} 
      </a> 
    </h2>

    <blockquote><p> {{ post.subtitle }} 
                    <!-- <time datetime="{{ post.date | date: '%Y-%m-%d' }}">({{ post.date | date: "%-d %B %Y" }})</time>   -->
                </p>
    </blockquote>

{% endfor %}

</div>

##  Contact Us

Most group discussion happens in other forums. To contact the group use either:

* [Ask questions on StackOverflow](http://stackoverflow.com/tags/f%23/info)
* [Post to our Google Group](http://groups.google.com/group/fsharp-opensource)
* [Propose or discuss an F# language feature](https://github.com/fsharp/fslang-suggestions) - please check for duplicates first
* [Contribute an issue to the F# compiler and library](http://fsharp.github.io/2014/06/18/fsharp-contributions.html)
* [Contribute an issue to other core repositories](http://github.com/fsharp)
* [Contribute an issue to other F# community incubation projects](http://github.com/fsprojects)

If you are using a package F# from Xamarin, Microsoft or another company you should contact them via their support for any issues or questions. The may refer you to one of our forums for some specific issues.
