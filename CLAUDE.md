# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Minimal Resume is a single-page personal resume website built with vanilla HTML, CSS, and JavaScript. No build tools or frameworks are required.

## Running the Project

Simply open `index.html` in a browser. No build steps, servers, or dependencies needed.

## Project Structure

- `SPEC.md` - Design specification document (Chinese)
- `index.html` - Single-page resume (HTML structure only)
- `style.css` - All CSS styles
- `script.js` - Vanilla JavaScript for interactions

## Customization

Resume data is embedded in `index.html`. Update your information in the HTML body:
- Name: Around lines 30-40
- Email: Around lines 55-60
- Phone: Around line 60
- Location: Around line 65
- Bio: Around line 45
- Skills: Around lines 75-105
- Projects: Around lines 115-175

## Architecture

Three-file structure:
- `style.css` - CSS custom properties for theming
- `script.js` - Vanilla JavaScript for scroll effects, mobile menu, and Intersection Observer animations
- `index.html` - HTML structure with Google Fonts: Playfair Display (headings), DM Sans (body)
- Mobile-first responsive breakpoints at 768px and 1024px

## Design System

- Black/white/gray color palette (no colors)
- 80px fixed nav height
- 120px section padding (desktop), 80px (mobile)
- Card shadows with hover states
- Smooth cubic-bezier transitions


# 项目规范
1. 代码结构：HTML、CSS、JS 分开存放。
2. 代码风格：使用 2 个空格进行缩进，变量命名使用驼峰命名法。
3. 工作流：每次修改代码后，都要进行代码审查，确保代码质量。
4. 设计规范：使用极简高级风格，配色以黑白灰为主。