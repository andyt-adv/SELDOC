# BARS implementation

This project will setup BARS for SELDOC who will be receiving referrals from external services.

At the time of the project kick off call they have limited knowledge of BARS and have asked to mirror the current ITK implementation.

- Checking the configuration in training and live there appears to be some previous setup for BARS services to recieve appointment bookings.

## Training configuration

The training system has been setup with the menu items

    *   Application configuration maintenance (BARS) filtered to CATEGORY=BARS
    *   Bookings and Referral Service Maintenance
    *   Outcome Mapping Maintenance (BARS) filtered to API_BARS

The existing APINHS111 outcome mappings have been duplicated and inserted as API_BARS mappings to mirror the existing service ID's and Outcome code behaviours.

Currently waiting on the customer to provide testing DoS service ID's to setup in training and map accordingly.