## API Report File for "@fluentui/react-drawer"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

/// <reference types="react" />

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import { DialogProps } from '@fluentui/react-dialog';
import { DialogSurfaceProps } from '@fluentui/react-dialog';
import { DialogSurfaceSlots } from '@fluentui/react-dialog';
import { DialogTitleSlots } from '@fluentui/react-dialog';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import * as React_2 from 'react';
import type { Slot } from '@fluentui/react-utilities';
import type { SlotClassNames } from '@fluentui/react-utilities';

// @public
export const Drawer: ForwardRefComponent<DrawerProps>;

// @public
export const DrawerBody: ForwardRefComponent<DrawerBodyProps>;

// @public (undocumented)
export const drawerBodyClassNames: SlotClassNames<DrawerBodySlots>;

// @public
export type DrawerBodyProps = ComponentProps<DrawerBodySlots>;

// @public (undocumented)
export type DrawerBodySlots = {
    root: Slot<'div'>;
};

// @public
export type DrawerBodyState = ComponentState<DrawerBodySlots>;

// @public
export const DrawerFooter: ForwardRefComponent<DrawerFooterProps>;

// @public (undocumented)
export const drawerFooterClassNames: SlotClassNames<DrawerFooterSlots>;

// @public
export type DrawerFooterProps = ComponentProps<DrawerFooterSlots>;

// @public (undocumented)
export type DrawerFooterSlots = {
    root: Slot<'footer'>;
};

// @public
export type DrawerFooterState = ComponentState<DrawerFooterSlots>;

// @public
export const DrawerHeader: ForwardRefComponent<DrawerHeaderProps>;

// @public (undocumented)
export const drawerHeaderClassNames: SlotClassNames<DrawerHeaderSlots>;

// @public
export const DrawerHeaderNavigation: ForwardRefComponent<DrawerHeaderNavigationProps>;

// @public (undocumented)
export const drawerHeaderNavigationClassNames: SlotClassNames<DrawerHeaderNavigationSlots>;

// @public
export type DrawerHeaderNavigationProps = ComponentProps<DrawerHeaderNavigationSlots>;

// @public (undocumented)
export type DrawerHeaderNavigationSlots = {
    root: Slot<'nav'>;
};

// @public
export type DrawerHeaderNavigationState = ComponentState<DrawerHeaderNavigationSlots>;

// @public
export type DrawerHeaderProps = ComponentProps<DrawerHeaderSlots>;

// @public (undocumented)
export type DrawerHeaderSlots = {
    root: Slot<'header'>;
};

// @public
export type DrawerHeaderState = ComponentState<DrawerHeaderSlots>;

// @public
export const DrawerHeaderTitle: ForwardRefComponent<DrawerHeaderTitleProps>;

// @public (undocumented)
export const drawerHeaderTitleClassNames: SlotClassNames<DrawerHeaderTitleSlots>;

// @public
export type DrawerHeaderTitleProps = ComponentProps<DrawerHeaderTitleSlots> & {
    children: React_2.ReactNode | undefined;
};

// @public (undocumented)
export type DrawerHeaderTitleSlots = {
    root: Slot<'div'>;
    heading?: DialogTitleSlots['root'];
    action?: DialogTitleSlots['action'];
};

// @public
export type DrawerHeaderTitleState = ComponentState<DrawerHeaderTitleSlots>;

// @public
export const DrawerInline: ForwardRefComponent<DrawerInlineProps>;

// @public (undocumented)
export const drawerInlineClassNames: SlotClassNames<DrawerInlineSlots>;

// @public
export type DrawerInlineProps = ComponentProps<DrawerInlineSlots> & DrawerBaseProps & {
    separator?: boolean;
};

// @public (undocumented)
export type DrawerInlineSlots = {
    root: Slot<'div'>;
};

// @public
export type DrawerInlineState = ComponentState<DrawerInlineSlots> & DrawerInlineProps;

// @public
export const DrawerOverlay: ForwardRefComponent<DrawerOverlayProps>;

// @public (undocumented)
export const drawerOverlayClassNames: SlotClassNames<DrawerOverlaySlots>;

// @public
export type DrawerOverlayProps = ComponentProps<DrawerOverlaySlots> & DrawerBaseProps & Pick<DialogProps, 'modalType' | 'onOpenChange' | 'inertTrapFocus'>;

// @public (undocumented)
export type DrawerOverlaySlots = DialogSurfaceSlots & {
    root: Slot<DialogSurfaceProps>;
};

// @public
export type DrawerOverlayState = ComponentState<DrawerOverlaySlots> & DrawerBaseProps & {
    dialog: DialogProps;
};

// @public
export type DrawerProps = ComponentProps<Partial<DrawerSlots>> & {
    type?: 'inline' | 'overlay';
};

// @public (undocumented)
export type DrawerSlots = {
    root: Slot<DrawerOverlayProps | DrawerInlineProps>;
};

// @public
export type DrawerState = ComponentState<DrawerSlots>;

// @public
export const renderDrawer_unstable: (state: DrawerState) => JSX.Element;

// @public
export const renderDrawerBody_unstable: (state: DrawerBodyState) => JSX.Element;

// @public
export const renderDrawerFooter_unstable: (state: DrawerFooterState) => JSX.Element;

// @public
export const renderDrawerHeader_unstable: (state: DrawerHeaderState) => JSX.Element;

// @public
export const renderDrawerHeaderNavigation_unstable: (state: DrawerHeaderNavigationState) => JSX.Element;

// @public
export const renderDrawerHeaderTitle_unstable: (state: DrawerHeaderTitleState) => JSX.Element;

// @public
export const renderDrawerInline_unstable: (state: DrawerInlineState) => JSX.Element | null;

// @public
export const renderDrawerOverlay_unstable: (state: DrawerOverlayState) => JSX.Element;

// @public
export const useDrawer_unstable: (props: DrawerProps, ref: React_2.Ref<HTMLElement>) => DrawerState;

// @public
export const useDrawerBody_unstable: (props: DrawerBodyProps, ref: React_2.Ref<HTMLElement>) => DrawerBodyState;

// @public
export const useDrawerBodyStyles_unstable: (state: DrawerBodyState) => DrawerBodyState;

// @public
export const useDrawerFooter_unstable: (props: DrawerFooterProps, ref: React_2.Ref<HTMLElement>) => DrawerFooterState;

// @public
export const useDrawerFooterStyles_unstable: (state: DrawerFooterState) => DrawerFooterState;

// @public
export const useDrawerHeader_unstable: (props: DrawerHeaderProps, ref: React_2.Ref<HTMLElement>) => DrawerHeaderState;

// @public
export const useDrawerHeaderNavigation_unstable: (props: DrawerHeaderNavigationProps, ref: React_2.Ref<HTMLElement>) => DrawerHeaderNavigationState;

// @public
export const useDrawerHeaderNavigationStyles_unstable: (state: DrawerHeaderNavigationState) => DrawerHeaderNavigationState;

// @public
export const useDrawerHeaderStyles_unstable: (state: DrawerHeaderState) => DrawerHeaderState;

// @public
export const useDrawerHeaderTitle_unstable: (props: DrawerHeaderTitleProps, ref: React_2.Ref<HTMLDivElement>) => DrawerHeaderTitleState;

// @public
export const useDrawerHeaderTitleStyles_unstable: (state: DrawerHeaderTitleState) => DrawerHeaderTitleState;

// @public
export const useDrawerInline_unstable: (props: DrawerInlineProps, ref: React_2.Ref<HTMLElement>) => DrawerInlineState;

// @public
export const useDrawerInlineStyles_unstable: (state: DrawerInlineState) => DrawerInlineState;

// @public
export const useDrawerOverlay_unstable: (props: DrawerOverlayProps, ref: React_2.Ref<HTMLElement>) => DrawerOverlayState;

// @public
export const useDrawerOverlayStyles_unstable: (state: DrawerOverlayState) => DrawerOverlayState;

// (No @packageDocumentation comment for this package)

```