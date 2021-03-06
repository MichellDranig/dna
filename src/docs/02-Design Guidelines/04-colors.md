---
title: Colors
url: /docs/design-guidelines/colors
category: design-guidelines
primaryKeywords: design colour palette primary secondary midnight spring digital
secondaryKeywords: hex rgb hsl red yellow orange blue grey black green
---

A colour palette comprises primary and accent colours that can be used for illustration or to develop your brand colors. They’ve been designed to work harmoniously with each other. The colour palette starts with primary colours and secondary colours in a meaningful hierachy that conveys specific meanings.

> The following colour hierarchy was created to address some branding needs and also to keep it clear to users what is more important in the flow.

<div class="frctl-example colors">
    <div class="colors__convert">
        <ul class="colors__convert-list">
            <li class="colors__convert-item">
                <button type="button" id="toHex" class="colors__convert-button" active aria-label="Convert color codes to hex">Hex</button>
            </li>
            <li class="colors__convert-item">
                <button type="button" id="toRgb" class="colors__convert-button" aria-label="Convert color codes to RGB">RGB</button>
            </li>
            <li class="colors__convert-item">
                <button type="button" id="toHsl" class="colors__convert-button" aria-label="Convert color codes to HSL">HSL</button>
            </li>
        </ul>
    </div>
    {{#each colors}}
        <dl class="colors__section">
            {{#each this}}
                <div class="colors__palette">
                    <dt class="colors__title">{{@key}}</dt>
                    {{#each this}}
                        <dd class="colors__item">
                            <div class="colors__color-swatch" style="background-color: {{@this}};">
                                <code class="colors__color-name" data-bg-color="{{@this}}" data-scss-code="$ys-color-{{@key}}">{{@this}}</code>
                            </div>
                            <code class="colors__variable-name">
                                <span class="colors__variable-text">$ys-color-{{@key}}</span>
                            </code>
                        </dd>
                    {{/each}}
                </div>
            {{/each}}
        </dl>
    {{/each}}
</div>
