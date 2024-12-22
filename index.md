---
layout: default
title: Welcome to 0cuopen's Blog
---

# Welcome to 0cuopen's Blog

福岡在住の豚骨エンジニア🍜

仕事や趣味のことなど💻⛰️🎣

# Blogs

<div class="blog-container">
    <a href="my_startup_failure_story" class="blog-horizontal-card">
        <img src="assets/images/thumbnail.webp" alt="Blog Thumbnail" class="blog-thumbnail">
        <div class="blog-content">
            <h3 class="blog-title">起業戦記</h3>
            <p class="blog-description">実はコロナ大流行時に若気の至りで起業していたことがありました。新卒で入社した上場企業を1年足らずで退職しスキルも実績…</p>
        </div>
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
    background-color: #000;
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
}

</style>
