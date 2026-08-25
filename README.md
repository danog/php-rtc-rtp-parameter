# RTP Parameters

![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

RTP parameters define the configuration of a media stream in Real-time Transport Protocol, including codec information, payload types, SSRCs, header extensions, and RTCP settings.

## About this fork

This is the `danog/php-rtc-rtp-parameter` PHP 8.2+ fork used by MadelineProto. It is published separately from upstream and declares that it replaces `quasarstream/rtp-parameter`.

The forked stack keeps the upstream `quasarstream/*` dependency constraints for compatibility. Each `danog/php-rtc-*` package replaces its upstream counterpart, so consumers select the complete maintained stack by requiring the corresponding danog packages together.

## Requirements

- **PHP ≥ 8.2**

## Documentation

This package is part of the PHP WebRTC library. For complete documentation, examples, and API reference, visit:

[PHP WebRTC Documentation](https://www.quasarstream.com/php-webrtc)

## Credits

### Authors

- **Amin Yazdanpanah**  
  - Website: [aminyazdanpanah.com](https://www.aminyazdanpanah.com)
  - Email: [github@aminyazdanpanah.com](mailto:github@aminyazdanpanah.com)

- **Sana Moniri**  
  - GtiHub: [sanamoniri](https://github.com/sanamoniri)

## Reporting Issues

Found a bug? Please report it on our [issues](https://github.com/php-webrtc/RTPParameter/issues).

## License

BSD 3-Clause License. See [LICENSE](LICENSE) for details.
