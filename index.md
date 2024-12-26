---
layout: default
title: Welcome to 0Cuopen's Blog
description: 0Cuopenのブログです
image: https://0cuopen.net/assets/images/thumbnail.webp
---

# Welcome to 0Cuopen's Blog

福岡在住の豚骨エンジニア🍜

仕事や趣味のことなど💻⛰️🎣

# New Arrivals

<div class="blog-container">
    <a href="gear_of_the_year_2024" class="blog-horizontal-card">
        <img src="assets/images/n_box.JPG" alt="Blog Thumbnail" class="blog-thumbnail">
        <div class="blog-content">
            <h3 class="blog-title">GEAR OF THE YEAR 2024</h3>
            <p class="blog-description">趣味というか仕事柄というか、自然と戯れることが多いので今年のBEST BUYを適当に書いていきます。</p>
        </div>
    </a>
</div>
<div class="blog-container">
    <a href="what_is_api" class="blog-horizontal-card">
        <img src="assets/images/api_sequence.png" alt="Blog Thumbnail" class="blog-thumbnail">
        <div class="blog-content">
            <h3 class="blog-title">APIとは何か</h3>
            <p class="blog-description">バックエンドエンジニア（以下、BEエンジニア）は多くの場合、APIと呼ばれるものを作っています。例えば「iOSエンジニアです」と言われたら</p>
        </div>
    </a>
</div>
<div class="blog-container">
    <a href="my_startup_failure_story" class="blog-horizontal-card">
        <img src="assets/images/nagano_office.JPG" alt="Blog Thumbnail" class="blog-thumbnail">
        <div class="blog-content">
            <h3 class="blog-title">起業戦記</h3>
            <p class="blog-description">実はコロナ大流行時に若気の至りで起業していたことがありました。新卒で入社した上場企業を1年足らずで退職しスキルも実績もない</p>
        </div>
    </a>
</div>

# SNS

<div class="sns-links">
    <a href="https://x.com/0Cuopen" target="_blank" class="sns-link twitter">
        <img src="assets/images/x-logo-white.png" class="sns-logo">
    </a>
    <a href="https://www.wantedly.com/id/hiraku_endo" target="_blank" class="sns-link wantedly">
        <img src="assets/images/wantedly_logo_white.png" class="sns-logo">
    </a>
</div>

<style>
p {
    text-align: center;
}

.blog-container {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

.blog-horizontal-card {
    display: flex;
    align-items: center;
    text-decoration: none;
    background-color: #3a3a3a;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    transition: transform 0.3s, box-shadow 0.3s;
    max-width: 600px;
    width: 100%;
}

.blog-horizontal-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

.blog-thumbnail {
    width: 150px;
    height: 100px;
    object-fit: cover;
    flex-shrink: 0;
}

.blog-content {
    padding: 15px;
    flex: 1;
}

.blog-title {
    margin: 0 0 8px;
    font-size: 18px;
    color: #fff;
}

.blog-description {
    margin: 0;
    font-size: 14px;
    color: #666;
    display: -webkit-box;
    -webkit-box-orient: vertical;
    overflow: hidden;
    -webkit-line-clamp: 2;
    text-align: left;
}

.sns-links {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

.sns-link {
    width: 50px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: background-color 0.3s ease-in-out;
    overflow: hidden;
}

.sns-logo {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain;
    transition: opacity 0.3s ease-in-out;
}

.sns-link.twitter:hover .sns-logo {
    content: url("assets/images/x-logo-black.png");
}

.sns-link.wantedly:hover .sns-logo {
    content: url("assets/images/wantedly_logo_black.png");
}

.sns-link.wantedly {
    width: 90px;
    height: 90px;
}
</style>
