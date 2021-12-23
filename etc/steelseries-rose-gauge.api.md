## API Report File for "steelseries-rose-gauge"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import * as ss from 'steelseries';

// @public
export class Rose {
    constructor(canvas: HTMLCanvasElement | string, parameters?: RoseParams);
    getBackgroundColor: () => ss.BackgroundColor;
    getForegroundType: () => ss.ForegroundType;
    getFrameDesign: () => ss.ForegroundType;
    getOdoValue: () => number;
    getPointSymbols: () => string[];
    getTitleString: () => string;
    getUnitString: () => string;
    getValue: () => number[];
    repaint: () => void;
    setBackgroundColor: (newBackgroundColor: ss.BackgroundColor) => this;
    setForegroundType: (newForegroundType: ss.ForegroundType) => this;
    setFrameDesign: (newFrameDesign: ss.FrameDesign) => this;
    setOdoValue: (newValue: number) => this;
    setOdoValueAnimated: (newValue: number, callback?: () => void) => this;
    setPointSymbols: (newPointSymbols: string[]) => this;
    setTitleString: (newTitle: string | number) => this;
    setUnitString: (newUnit: string) => this;
    setValue: (newValue: number[]) => this;
}

// @public
export interface RoseParams {
    backgroundColor?: ss.BackgroundColor;
    backgroundVisible?: boolean;
    foregroundType?: ss.ForegroundType;
    foregroundVisible?: boolean;
    frameDesign?: ss.FrameDesign;
    frameVisible?: boolean;
    odometerParams?: ss.OdometerParams;
    pointSymbols?: string[];
    size?: number;
    titleString?: string;
    unitString?: string;
    useOdometer?: boolean;
}

```