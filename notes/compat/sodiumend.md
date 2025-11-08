# Making Sodium 0.6 & BetterEnd 21.0.11+ compatible
> [!CAUTION]
> There is a small chance you may experience corruptions. **This fix is not guarenteed to work**.

If you use Sodium 0.6.13 and you want to use BetterEnd together, there's a few steps you have to perform. **This requires file editing.**

Note that I am not a professional. All advice comes from [this issue thread](https://github.com/CaffeineMC/sodium/issues/2869).

## 1. Disable sulfur_water_color
Open .minecraft (or the instance folder, if you are using a custom launcher), and go to `config/betterend/client.json`.

Change `sulfur_water_color` to `false`.

## 2. Set a custom dependancy override
Leave the BetterEnd folder but **stay in config**. Create the file `???` if it doesn't exist.

Now, in that file, copy the JSON data from [this comment's instructions](https://github.com/CaffeineMC/sodium/issues/2869#issuecomment-2817351635) and paste it in that file.

If there's already stuff in that file, you may need to know some JSON to make the overrides work together.

## 3. Boot and have fun!

# Sources
- [BetterEnd causes "Missing palette entry for index..." crashes when loading chunks](https://github.com/CaffeineMC/sodium/issues/2869)