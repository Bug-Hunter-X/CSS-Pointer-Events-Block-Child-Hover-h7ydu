# CSS Pointer Events Blocking Child Hover Issue

This repository demonstrates a common yet easily overlooked issue in CSS where the `pointer-events: none` property on a parent element prevents hover effects from working on its child elements.  The problem and its solution are shown using simple CSS code examples.

## Problem

When `pointer-events: none` is applied to a parent element, it prevents mouse events (including `hover`) from propagating to its children.  This can lead to unexpected behavior where hover effects intended for child elements are not triggered.

## Solution

The solution involves careful consideration of how `pointer-events` is used.  Sometimes, adjusting the specificity or using a different approach is necessary to achieve the desired effect.