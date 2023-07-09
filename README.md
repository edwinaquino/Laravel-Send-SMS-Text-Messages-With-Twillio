# Laravel Send SMS Text Messages With Twillio

This is a simple example of a Laravel Project to show how to send SMS text messaging using various providers. This example uses Twilio as the provider.

## Installation

Follow these steps to get you stared.

1. Clone and install the required packages.
```bash
$ git clone https://github.com/edwinaquino/Laravel-Send-SMS-Text-Messages-With-Twillio.git
$ cd Laravel-Send-SMS-Text-Messages-With-Twillio
$ composer install
```
2. Create a Free Twillio account to obtain a Token. https://www.twilio.com/

3. Copy .env-example

```bash
$ cp .env-example .env
```
4. Add your TOKEN information into the .env file:
```bash
TWILIO_SID=xxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_TOKEN=xxxxxxxxxxxxxxxxx
TWILIO_FROM=+12135551212
```
5. Run the application
```bash
$ php artisan serve
```
6. Open url in Browser:
```bash
Server running on [http://127.0.0.1:8001]
```
## Source
/f/apachefriends/xampp/htdocs/over-imgV5/REACT/SMS/Twilio/Laravel/send-sms-with-twillio

## Screen Shot
<img width="395" alt="github-how-to-send-sms-laravel" src="https://github.com/edwinaquino/Laravel-Send-SMS-Text-Messages-With-Twillio/assets/30946443/6150ca30-5d67-40af-b731-ed4d13951367"></img>

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Resources:
* https://github.com/twilio-professional-services/twilio-webchat-with-serverless
* https://www.youtube.com/watch?v=YPOce95TbAc

## Notes
To install Twillio SDK:
```
$ composer require twilio/sdk
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
