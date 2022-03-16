# A modified version of Hack font

Modefied the [Hack font](https://github.com/source-foundry/Hack) with some characters like "i", "1" and "0" (hinted by ttfautohint)

:point_right: goto [release page ](https://github.com/ghsgz/a-custom-Hack-Font/releases) to download and use.

<br>

Previews:

<p align="center">
  <img src="https://github.com/ghsgz/a-custom-Hack-Font/blob/master/screenshots/screenshot_2022.png" width="720"><br>
  <code>in Win10 VSCode(2560*1600)</code><br>
</p>

<p align="center">
  <img src="https://github.com/ghsgz/a-custom-Hack-Font/blob/master/screenshots/screenshot.png" max-width="720"><br>
  <code>in Win10 Gvim(1366*768)</code><br>
</p>


<br>

## Notes

- you may experience problems while customizing Hack font with [alt-hack](https://github.com/source-foundry/alt-hack) repo. Trackback Error may like this:

```shell
Warning: Option `-w G' is deprecated!  Use option `-a qsq' instead
postbuild_processing/tt-hinting/Hack-Regular-TA.txt:3:1: invalid glyph name (0x204)
  numbersign touch 0,1,2,3,18,19,20,21,22,23,24,25,26,27,28,31 x 0.25  @ 13
  ^
Unable to execute ttfautohint on the Hack-Regular variant set.  Build canceled.
```

According to [issue 482](https://github.com/source-foundry/Hack/issues/482) from [Hack](https://github.com/source-foundry/Hack) repository issue lists, we need comment out all uncommented lines in these files: `<Hack-src-root-path>/postbuild_processing/tt-hinting/*.txt`.

- Hack font is a great font for me! I :heart: Hack!
- the orginal Hack font looks like below:
<p align="center">
  <img src="https://sourcefoundry.org/hack/assets/img/mockup/Aa-mockup-2.png" width="720">
</p>
