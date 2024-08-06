# Cognifyz-level3-task1

# Bulma Card Component - README

## Introduction

This README file provides detailed information about the Bulma Card component, a part of the Bulma CSS framework. Bulma is a modern CSS framework based on Flexbox, offering easy-to-use classes for creating responsive web interfaces. The Card component is a versatile, customizable content container that can include various elements like images, titles, and text.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Basic Usage](#basic-usage)
3. [Card Components](#card-components)
4. [Customization](#customization)
5. [Examples](#examples)
6. [License](#license)

## Getting Started

### Prerequisites

To use Bulma and its Card component, you'll need a basic understanding of HTML and CSS. Additionally, you'll need to include the Bulma CSS file in your project.

### Installation

You can include Bulma in your project by using a CDN, downloading the CSS file, or installing it via npm.

#### Using CDN

Add the following `<link>` tag to the `<head>` of your HTML document:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.3/css/bulma.min.css">
```

#### Using npm

If you prefer using npm, install Bulma by running:

```sh
npm install bulma
```

Then, include Bulma in your CSS file:

```css
@import 'bulma/css/bulma.css';
```

## Basic Usage

The basic structure of a Bulma Card is as follows:

```html
<div class="card">
  <div class="card-content">
    <p class="title">
      Card Title
    </p>
    <p class="subtitle">
      Card Subtitle
    </p>
    <div class="content">
      Card content goes here.
    </div>
  </div>
</div>
```

## Card Components

### 1. Card Container

The outermost container of the card is the `<div class="card">`.

### 2. Card Content

The main content of the card is wrapped in `<div class="card-content">`. Inside this container, you can add titles, subtitles, and other content.

### 3. Card Header

The card header is optional and can be used to include a title or an icon.

```html
<div class="card">
  <header class="card-header">
    <p class="card-header-title">
      Card Header Title
    </p>
    <button class="card-header-icon" aria-label="more options">
      <span class="icon">
        <i class="fas fa-angle-down" aria-hidden="true"></i>
      </span>
    </button>
  </header>
</div>
```

### 4. Card Image

If your card includes an image, you can use the following structure:

```html
<div class="card">
  <div class="card-image">
    <figure class="image is-4by3">
      <img src="path-to-image.jpg" alt="Placeholder image">
    </figure>
  </div>
</div>
```

### 5. Card Footer

The card footer can be used to add links or other actions.

```html
<div class="card">
  <footer class="card-footer">
    <a href="#" class="card-footer-item">Footer Link 1</a>
    <a href="#" class="card-footer-item">Footer Link 2</a>
  </footer>
</div>
```

## Customization

### Colors

You can customize the colors of the card by adding Bulma's color classes.

```html
<div class="card has-background-primary">
  <div class="card-content has-text-white">
    Card with a primary background color.
  </div>
</div>
```

### Sizes

You can adjust the size of the card using Bulma's size classes.

```html
<div class="card is-small">
  Small card.
</div>

<div class="card is-medium">
  Medium card.
</div>

<div class="card is-large">
  Large card.
</div>
```

## Examples

### Simple Card

```html
<div class="card">
  <div class="card-content">
    <p class="title">
      Simple Card
    </p>
    <p class="subtitle">
      Subtitle
    </p>
    <div class="content">
      This is a simple card example.
    </div>
  </div>
</div>
```

### Card with Image and Footer

```html
<div class="card">
  <div class="card-image">
    <figure class="image is-4by3">
      <img src="path-to-image.jpg" alt="Placeholder image">
    </figure>
  </div>
  <div class="card-content">
    <p class="title">
      Card Title
    </p>
    <p class="subtitle">
      Subtitle
    </p>
    <div class="content">
      This card has an image and a footer.
    </div>
  </div>
  <footer class="card-footer">
    <a href="#" class="card-footer-item">Footer Link 1</a>
    <a href="#" class="card-footer-item">Footer Link 2</a>
  </footer>
</div>
```

## License

Bulma is an open-source project licensed under the MIT License. For more information, please refer to the [official Bulma documentation](https://bulma.io/documentation/overview/start/).

---

By following this guide, you should be able to create and customize Bulma Cards to fit the needs of your web project. If you have any questions or need further assistance, refer to the [Bulma documentation](https://bulma.io/documentation/).
