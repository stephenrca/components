## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { _AbstractConstructor } from '@angular/material/core';
import { CanColor } from '@angular/material/core';
import { ChangeDetectorRef } from '@angular/core';
import { _Constructor } from '@angular/material/core';
import { ElementRef } from '@angular/core';
import * as i0 from '@angular/core';
import * as i2 from '@angular/material/core';
import * as i3 from '@angular/common';
import { ProgressSpinnerMode as LegacyProgressSpinnerMode } from '@angular/material/progress-spinner';
import { MAT_PROGRESS_SPINNER_DEFAULT_OPTIONS as MAT_LEGACY_PROGRESS_SPINNER_DEFAULT_OPTIONS } from '@angular/material/progress-spinner';
import { MAT_PROGRESS_SPINNER_DEFAULT_OPTIONS_FACTORY as MAT_LEGACY_PROGRESS_SPINNER_DEFAULT_OPTIONS_FACTORY } from '@angular/material/progress-spinner';
import { MatProgressSpinnerDefaultOptions as MatLegacyProgressSpinnerDefaultOptions } from '@angular/material/progress-spinner';
import { NgZone } from '@angular/core';
import { NumberInput } from '@angular/cdk/coercion';
import { OnDestroy } from '@angular/core';
import { OnInit } from '@angular/core';
import { Platform } from '@angular/cdk/platform';
import { ViewportRuler } from '@angular/cdk/scrolling';

export { LegacyProgressSpinnerMode }

export { MAT_LEGACY_PROGRESS_SPINNER_DEFAULT_OPTIONS }

export { MAT_LEGACY_PROGRESS_SPINNER_DEFAULT_OPTIONS_FACTORY }

// @public @deprecated
export class MatLegacyProgressSpinner extends _MatProgressSpinnerBase implements OnInit, OnDestroy, CanColor {
    constructor(elementRef: ElementRef<HTMLElement>, _platform: Platform, _document: any, animationMode: string, defaults?: MatLegacyProgressSpinnerDefaultOptions,
    changeDetectorRef?: ChangeDetectorRef, viewportRuler?: ViewportRuler, ngZone?: NgZone, _nonce?: string | null | undefined);
    get diameter(): number;
    set diameter(size: NumberInput);
    _getCircleRadius(): number;
    _getCircleStrokeWidth(): number;
    _getCircleTransformOrigin(svg: HTMLElement): string;
    _getStrokeCircumference(): number;
    _getStrokeDashOffset(): number | null;
    _getViewBox(): string;
    mode: LegacyProgressSpinnerMode;
    // (undocumented)
    ngOnDestroy(): void;
    // (undocumented)
    ngOnInit(): void;
    _noopAnimations: boolean;
    _spinnerAnimationLabel: string;
    get strokeWidth(): number;
    set strokeWidth(value: NumberInput);
    get value(): number;
    set value(newValue: NumberInput);
    // (undocumented)
    static ɵcmp: i0.ɵɵComponentDeclaration<MatLegacyProgressSpinner, "mat-progress-spinner, mat-spinner", ["matProgressSpinner"], { "color": { "alias": "color"; "required": false; }; "diameter": { "alias": "diameter"; "required": false; }; "strokeWidth": { "alias": "strokeWidth"; "required": false; }; "mode": { "alias": "mode"; "required": false; }; "value": { "alias": "value"; "required": false; }; }, {}, never, never, false, never, false>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatLegacyProgressSpinner, [null, null, { optional: true; }, { optional: true; }, null, null, null, null, { optional: true; }]>;
}

export { MatLegacyProgressSpinnerDefaultOptions }

// @public @deprecated (undocumented)
export class MatLegacyProgressSpinnerModule {
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<MatLegacyProgressSpinnerModule, never>;
    // (undocumented)
    static ɵinj: i0.ɵɵInjectorDeclaration<MatLegacyProgressSpinnerModule>;
    // (undocumented)
    static ɵmod: i0.ɵɵNgModuleDeclaration<MatLegacyProgressSpinnerModule, [typeof i1.MatLegacyProgressSpinner], [typeof i2.MatCommonModule, typeof i3.CommonModule], [typeof i1.MatLegacyProgressSpinner, typeof i2.MatCommonModule]>;
}

// @public @deprecated (undocumented)
export const MatLegacySpinner: typeof MatLegacyProgressSpinner;

// (No @packageDocumentation comment for this package)

```
