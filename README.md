# OVOS Shell companion

provides various bus APIs that integrate with ovos-shell
    
    - color scheme manager
    - notifications widgets
    - configuration provider  (settings UI)
    - brightness control  (night mode etc)
    - dashboard manager  (TODO deprecate)
    

these used to be several individual plugins but they all are ovos-shell specific integrations and ovos-shell requires all of them, so they have been unified


the following packages have been deprecated in favor of this repo:
- https://github.com/OpenVoiceOS/ovos-PHAL-plugin-dashboard
- https://github.com/OpenVoiceOS/ovos-PHAL-plugin-configuration-provider
- https://github.com/OpenVoiceOS/ovos-PHAL-plugin-notification-widgets
- https://github.com/OpenVoiceOS/ovos-PHAL-plugin-brightness-control-rpi
- https://github.com/OpenVoiceOS/ovos-PHAL-plugin-color-scheme-manager
