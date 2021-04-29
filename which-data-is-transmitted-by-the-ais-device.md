# Which data is transmitted by the AIS device?

Data transmitted by the Inland AIS station should always be accurate and up to date, according to article 4.07 \(2\) of the Rhine Police Regulations. It is the skipper’s responsibility to ensure that all data transmitted by the AIS station matches the vessel’s or convoy’s current data.

Vessels fitted with AIS transmit and receive information on an automatic and periodical basis from other ships equipped with AIS. This information regards the vessel and its current nautical data:

* Identity of the vessel
* Its exact position
* Its course and speed
* Other ship-specific data

However some data must be enterred manually by the skipper. The most prominent of which are :

* navigational status of the vessel \(e.g. under way, moored or at anchor\)
* Type of vessel / convoy
* Overall length and beam of the vessel / convoy

{% page-ref page="navigational-status.md" %}

## List of data that must be transmitted by the Inland AIS device

There is a minimum set of data transmitted by the AIS station which needs to be available at all times and kept up to date.

The minimum data set of an Inland AIS station is according to article 4.07 \(4\) of the Rhine Police Regulations:

| Dataset | Description | When update the data  |
| :--- | :--- | :--- |
| MMSI | Maritime Mobile Service Identity = AIS device identity | [Each installation](which-data-is-transmitted-by-the-ais-device.md#settings-defined-during-installation-of-the-inland-ais-device) |
| Vessel name | Usual name of the Vessel on VHF channels | [Each installation](which-data-is-transmitted-by-the-ais-device.md#settings-defined-during-installation-of-the-inland-ais-device) |
| Call sign | VHF radio call sign of the vessel | [Each installation](which-data-is-transmitted-by-the-ais-device.md#settings-defined-during-installation-of-the-inland-ais-device) |
| Vessel type or convoy type | List of vessel and convoy | [Each voyage](which-data-is-transmitted-by-the-ais-device.md#entering-data-in-the-inland-ais-device) |
| ENI | unique European vessel Identification Number \(ENI\) or, for seagoing vessels that have not been given an ENI number, the IMO number | [Each installation](which-data-is-transmitted-by-the-ais-device.md#settings-defined-during-installation-of-the-inland-ais-device) |
| Length | overall length of the vessel or convoy accurate to 0.1 m | [Each voyage](which-data-is-transmitted-by-the-ais-device.md#entering-data-in-the-inland-ais-device) |
| breadth  | overall breadth of the vessel or convoy accurate to 0.1 m | [Each voyage](which-data-is-transmitted-by-the-ais-device.md#entering-data-in-the-inland-ais-device) |
| reference point | reference point for the positional information aboard the vessel, accurate to 1 m, \(this is the position of the GPS antenna of the Inland AIS station\) see Annex 2. | [Each voyage](which-data-is-transmitted-by-the-ais-device.md#entering-data-in-the-inland-ais-device) |
| GNSS position | Position of the vessel \(derived from GPS in WGS 84 coordinate system\) | [Automatic](which-data-is-transmitted-by-the-ais-device.md#data-automatically-determined-by-the-inland-ais-device) |
| Time | time indication of position determination by the electronic position location device | [Automatic](which-data-is-transmitted-by-the-ais-device.md#data-automatically-determined-by-the-inland-ais-device) |
| SOG | speed over ground | [Automatic](which-data-is-transmitted-by-the-ais-device.md#data-automatically-determined-by-the-inland-ais-device) |
| COG | course over ground | [Automatic](which-data-is-transmitted-by-the-ais-device.md#data-automatically-determined-by-the-inland-ais-device) |
| NavStat | Navigational status | [Each Manoeuvre](navigational-status.md) |

Inland AIS can provide more data but this is not mandatory, and the data can be entered voluntarily.  

As transmitting additional data has often proved to be a source of confusion, it is recommended that only the mandatory data listed above be transmitted and additional data such as information on the vessel’s voyage should not be transmitted.

The following checklist contains a checklist contains tasks to be performed before, during and after the voyage including the change of convoy data if necessary

{% page-ref page="voyage-checklist.md" %}

## Entering data in the Inland AIS device

Data that the skipper must check Inland AIS data at least once before each voyage. For example, the setting of the convoy may change depending on the voyage.

When the convoy setting is changed, The skipper needs to update  :

* Vessel or convoy type
* Position of the reference point \(GPS Antenna\)

{% page-ref page="reference-point-for-the-positional-information.md" %}

{% hint style="danger" %}
Check the position unit required by the Inland AIS device \(metres or decimetres for example\)
{% endhint %}

By way of an example, for a convoy with a breadth of 12.54 m, the skipper enters 12.6 m or 126 dm in the Inland AIS device, depending on the unit required by the device.

For vessels that never sail in a convoy, the vessel type and the position of the reference point are entered by the approved specialised firm one for good during installation of the device.

### For convoys :

{% page-ref page="how-to-set-a-convoy-or-a-towed-convoy-in-the-inland-ais-device.md" %}

### **Data automatically determined by the Inland AIS device**

The skipper does not need to make any adjustments to the Inland AIS device for the data that are determined and transmitted automatically. These data are as follow:

* position \(WGS84 coordinates\) of the vessel or convoy on which the Inland AIS device is installed,
* speed over ground,
* course over ground,
* time indicated by the electronic position location device.

### Settings defined during installation of the Inland AIS device

{% hint style="info" %}
These settings must be amended following a modification of the vessel \(example: change of owner of the vessel, change of name of the vessel, lengthening of the vessel\)
{% endhint %}

The settings listed below is entered when the Inland AIS device is installed. This initial setting \(and any subsequent amendment \) must be carried out by an approved specialised firm. However, the skipper must ensure that the approved specialised firm enters the data correctly:

* AIS station identity \(MMSI\)
* vessel name
* call sign \(VHF radio of the vessel\)
* unique European vessel Identification Number \(ENI\)
* overall length of the vessel referred to the on-board GPS antenna, accurate to 0.1 m
* overall breadth of the vessel referred to the on-board GPS antenna, accurate to 0.1 m
* vessel type

### **Transmitting of incorrect data by the Inland AIS device**

The skipper should regularly check if the transmitted data by the Inland AIS station are correct. This can be done by reviewing the settings in the appropriate menus of the Inland AIS station \(refer to the user manual of the Inland AIS device\).

In rare cases the Inland AIS device can transmit incorrect data without the skipper being aware of it. Consequently, the CCNR recommends that other skippers take the initiative in contacting the skipper of the vessel whose Inland AIS device is transmitting incorrect data to alert him.

The skipper must immediately correct the data or initiate a correction by the approved specialised firm. Failure to act on this request shall render him liable to prosecution.

### \*\*\*\*

