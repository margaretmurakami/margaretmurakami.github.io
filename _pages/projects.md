---
title: "Projects"
permalink: /projects/
layout: gridlay
sitemap: false

feature_row_1:
  - image_path: /images/jsg.jpg
    image_caption: "Source: "
    alt: "Test"
    title: "Book Review: Michael Shellenberger"
    excerpt: "Calibrating ice sheet model SICOPOLIS using age layer radar data in order to project the future impact on sea level accurately."
    url: /shellenberger/
    btn_label: "Read More"
    btn_class: "btn--primary"

---
<style>
    .jumbotron {
        padding: 3%;
        padding-bottom: 10px;
        padding-top: 10px;
        margin-top: 10px;
        margin-bottom: 30px;
    }
    .feature__item {
        position: relative;
        margin-bottom: 2em;
        font-size: 1.125em
    }
    .feature__item--left .archive__item {
        float: left
    }
    .feature__item--left .archive__item-teaser {
        margin-bottom: 2em
    }
    .archive__item-caption {
        position: absolute;
        bottom: 0;
        right: 0;
        margin: 0 auto;
        padding: 2px 5px;
        color: #fff;
        font-family: Georgia,Times,serif;
        font-size: .625em;
        background: #000;
        text-align: right;
        z-index: 5;
        opacity: 0.5;
        border-radius: 4px 0 0 0
    }

    @media (min-width: 64em) {
        .archive__item-caption {
            padding:5px 10px
        }  
    }
    .archive__item-caption a {
        color: #fff;
        text-decoration: none
    }
    .feature__item .archive__item-body {
        padding-left: 1.6949152542%;
        padding-right: 1.6949152542%
    }
    @media (min-width: 37.5em) {
        .feature__item--left .archive__item-teaser {
            float:left;
            width: 40.6779661017%
        }

        .feature__item--left .archive__item-body {
            float: right;
            padding-left: 1.6949152542%;
            padding-right: 1.6949152542%;
            width: 57.6271186441%
        }
    }
    .archive__item-title {
        margin-bottom: 0.25em;
        font-family: -apple-system,BlinkMacSystemFont,"Roboto","Segoe UI","Helvetica   Neue","Lucida Grande",Arial,sans-serif;
        line-height: initial;
        overflow: hidden;
        text-overflow: ellipsis
    }
    .archive__item-title a[rel="permalink"]::before {
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0
    }

    .archive__item-title a+a {
    opacity: 0.5
    }

    .page__content .archive__item-title {
    margin-top: 1em;
    border-bottom: none
    }
    .archive__item-excerpt .ais-Highlight {
    color: red;
    font-style: normal;
    font-weight: bold
    }
    .archive__item-excerpt {
    margin-top: 0;
    font-size: .75em
    }
    .archive__item-excerpt+p {
    text-indent: 0
    }
    .archive__item-excerpt a {
    position: relative
    }
</style>

<div class="feature__item">
    <div class="archive__item">
        <div class="archive__item-teaser">
            <img src="/images/shellenberger.jpg" alt="Test">
            <span class="archive__item-caption">Source: </span>
        </div>
        <div class="archive__item-body">
            <h2 class="archive__item-title">Book Review: Michael Shellenberger</h2>
            <div class="archive__item-excerpt">
                <p>Review of a 2020 book by Michael Shellenberger.</p>
            </div>
            <p><a href="/shellenberger/" class="btn btn--primary">Read More</a></p>
        </div>
    </div>
</div>
