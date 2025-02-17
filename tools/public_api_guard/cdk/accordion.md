## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BooleanInput } from '@angular/cdk/coercion';
import { ChangeDetectorRef } from '@angular/core';
import { EventEmitter } from '@angular/core';
import * as i0 from '@angular/core';
import { InjectionToken } from '@angular/core';
import { OnChanges } from '@angular/core';
import { OnDestroy } from '@angular/core';
import { SimpleChanges } from '@angular/core';
import { Subject } from 'rxjs';
import { UniqueSelectionDispatcher } from '@angular/cdk/collections';

// @public
export class CdkAccordion implements OnDestroy, OnChanges {
    closeAll(): void;
    readonly id: string;
    get multi(): boolean;
    set multi(multi: BooleanInput);
    // (undocumented)
    ngOnChanges(changes: SimpleChanges): void;
    // (undocumented)
    ngOnDestroy(): void;
    openAll(): void;
    readonly _openCloseAllActions: Subject<boolean>;
    readonly _stateChanges: Subject<SimpleChanges>;
    // (undocumented)
    static ɵdir: i0.ɵɵDirectiveDeclaration<CdkAccordion, "cdk-accordion, [cdkAccordion]", ["cdkAccordion"], { "multi": { "alias": "multi"; "required": false; }; }, {}, never, never, false, never, false>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<CdkAccordion, never>;
}

// @public
export class CdkAccordionItem implements OnDestroy {
    constructor(accordion: CdkAccordion, _changeDetectorRef: ChangeDetectorRef, _expansionDispatcher: UniqueSelectionDispatcher);
    // (undocumented)
    accordion: CdkAccordion;
    close(): void;
    readonly closed: EventEmitter<void>;
    readonly destroyed: EventEmitter<void>;
    get disabled(): boolean;
    set disabled(disabled: BooleanInput);
    get expanded(): boolean;
    set expanded(expanded: BooleanInput);
    readonly expandedChange: EventEmitter<boolean>;
    // (undocumented)
    protected _expansionDispatcher: UniqueSelectionDispatcher;
    readonly id: string;
    ngOnDestroy(): void;
    open(): void;
    readonly opened: EventEmitter<void>;
    toggle(): void;
    // (undocumented)
    static ɵdir: i0.ɵɵDirectiveDeclaration<CdkAccordionItem, "cdk-accordion-item, [cdkAccordionItem]", ["cdkAccordionItem"], { "expanded": { "alias": "expanded"; "required": false; }; "disabled": { "alias": "disabled"; "required": false; }; }, { "closed": "closed"; "opened": "opened"; "destroyed": "destroyed"; "expandedChange": "expandedChange"; }, never, never, false, never, false>;
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<CdkAccordionItem, [{ optional: true; skipSelf: true; }, null, null]>;
}

// @public (undocumented)
export class CdkAccordionModule {
    // (undocumented)
    static ɵfac: i0.ɵɵFactoryDeclaration<CdkAccordionModule, never>;
    // (undocumented)
    static ɵinj: i0.ɵɵInjectorDeclaration<CdkAccordionModule>;
    // (undocumented)
    static ɵmod: i0.ɵɵNgModuleDeclaration<CdkAccordionModule, [typeof i1.CdkAccordion, typeof i2.CdkAccordionItem], never, [typeof i1.CdkAccordion, typeof i2.CdkAccordionItem]>;
}

// (No @packageDocumentation comment for this package)

```
