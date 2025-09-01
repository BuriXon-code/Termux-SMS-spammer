# Termux-SMS-spammer

## About ...

This is a Bash script for Termux that allows you to send multiple SMS messages to a specific phone number (or multiple numbers).

The script uses the termux-api package with the capabilities and permissions of the Termux:API application and the, coreutils and bash packages to execute a loop that sends SMS at specified intervals and in specified amounts.

![screenshot](/img1.jpg)

## Installation ...

To install the script, perform:

```
git clone https://github.com/BuriXon-code/Termux-SMS-spammer
cd Termux-SMS-spammer
chmod +x sms-spammer
```

## Usage ...

### For help and usage tips use:

```
./sms-spammer -h
```
### Usage examples:
```
sms-spammer -n 123456789 -s 1 -c 100 -d 5 -mt "test123"
```
```
sms-spammer -n 123456789,+987654321 -s 2 -c 5 -d 60 -mr 50
```

> [!NOTE]
> + You can enter multiple phone numbers separated by commas.
>
> + The phone number cannot contain spaces, even if it is enclosed in quotation marks.
>
> + SMS messages will start being sent to the next recipient only after all messages have been sent to the previous recipient.

![screenshot](/img2.jpg)

## Compatibility ...

The script for proper operation requires installed and configured Termux:API together with the termux-api package, Bash package installed.

It was tested in Termux 0.119-beta with Polish phone numbers.

> [!CAUTION]
> **In the event of significant abuse in terms of the count and content of sent SMS messages, the operator may block the user's SIM card.**

> [!TIP]
> Use wisely! :\)

![screenshot](/img3.jpg)

## Support
### Contact me:
For any issues, suggestions, or questions, reach out via:

- *Email:* support@burixon.dev  
- *Contact form:* [Click here](https://burixon.dev/contact/)
- *Bug reports:* [Click here](https://burixon.dev/bugreport/#Termux-SMS-spammer)

### Support me:
If you find this script useful, consider supporting my work by making a donation:

[**Donations**](https://burixon.dev/donate/)

Your contributions help in developing new projects and improving existing tools!
