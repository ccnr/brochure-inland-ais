# What are the most common data fields of Inland AIS device?

It is mandatory that Inland AIS device to transmit up-to-date . Therefore, this page will give some hints for the boatmaster and explains \(when applicable\) for what reasons the data are used. For the daily operations, the boatmaster can also make use of the [checklist](qr28.md).

<table>
  <thead>
    <tr>
      <th style="text-align:left">Data Field</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>User identity (MMSI number)</b>
      </td>
      <td style="text-align:left">The MMSI number is the identity number of the transmitting Inland AIS
        device and is assigned by the competent telecommunication administration
        and for on-board radio communication equipment. The assigned MMSI number
        is set by the specialized approved firm when installing the Inland AIS
        device. This number helps the authorities&apos; vessel traffic management
        systems to identify a vessel and connect it to current voyage data.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Name of the vessel</b>
      </td>
      <td style="text-align:left">The name of the vessel is set in the Inland AIS device by the specialized
        approved firm when installing it. The name of the vessel helps the boatmaster
        to identify traffic in the vicinity.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Vessel or convoy type</b>
      </td>
      <td style="text-align:left">The <em>vessel or convoy type</em> is used by vessel traffic management
        systems of the authorities in order to identify the composition of a convoy
        and/or to plan lock cycles. Inland AIS provides a list of different vessel
        and convoy types to choose from. For a convoy, the convoy type may change
        for each vessel depending on the number and type of the coupled barges.
        For some vessels, the type may also change. This needs to be updated by
        the boatmaster for each voyage.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>ENI number</b>
      </td>
      <td style="text-align:left">The ENI number is the Unique European vessel identification number. It
        is set by the specialized approved firm when installing the Inland AIS
        device. The ENI number is used by vessel traffic management systems of
        the authorities to identify vessels and connect them to their current voyage
        data.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Dimensions</b>
      </td>
      <td style="text-align:left">
        <p>The dimensions are the overall length and beam of the vessel or convoy.
          For a single vessel, those values are set by the specialized approved firm
          during installation of the Inland AIS device. For a convoy, the values
          must be set by the boatmaster according to the actual situation of the
          convoy. The boatmaster uses the dimensions of other vessels so as to ensure
          safe passing and overtaking.</p>
        <p>The authorities use the dimensions in their vessel traffic management
          systems for lock planning and/or VTS services</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Position</b>
      </td>
      <td style="text-align:left">The position is used for displaying the vessel on a map. This position
        information of a vessel reflects the actual position of the Inland AIS
        device&#x2019;s GPS antenna on board of the vessel. The position is used
        by other boatmasters and authorities.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Speed over ground</b>
      </td>
      <td style="text-align:left">
        <p>The speed over ground is transmitted automatically by the Inland AIS device.
          The boatmaster uses the speed to identify if a vessel is moving and at
          what speed.</p>
        <p>The vessel traffic management systems of authorities could use the speed
          over ground to identify if a vessel is moving. This allows to sort vessels
          which are underway from the one moored. .</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Course</b>
      </td>
      <td style="text-align:left">The course of the vessel is transmitted automatically by the Inland AIS
        device. It is used by the boatmaster and the authorities to determine the
        sailing direction of a vessel.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Navigational status</b>
      </td>
      <td style="text-align:left">The navigational status gives an indication about the operation status
        of the vessel (e.g. &#x2018;underway using engine&#x2019;, &#x2018;at anchor&#x2019;,
        &#x2018;moored&#x2019;) and is set under the responsibility of the boatmaster
        ). The vessel traffic management systems of the authorities use this information
        for planning purposes. The navigational status might not be so important
        for the boatmaster, but to be informed that an Inland AIS device that is
        transmitting &#x2018;Underway, using engine&#x2019; claims far more time-slots
        for transmitting in contrast to the navigational status &#x2018;Moored&#x2019;.
        In dense areas especially (such as ports) it helps to reduce the load to
        the system if the navigational status is set to &#x2018;Moored&#x2019;
        when a vessel is moored. The navigational status is set by the boatmaster
        but some suppliers (especially Inland ECDIS manufacturers) offer the feature
        of an (semi)automatic setting of the navigational status based on the speed
        over ground. Howewer the boatmaster is responsible for the transmitted
        information.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Reference point</b>
      </td>
      <td style="text-align:left">The reference point of the vessel is in most cases the position of the
        AIS device&#x2019;s GPS antenna. The reference point is set by the specialized
        approved firm during installation of the Inland AIS device. Only in the
        case of convoys does the reference point need to be changed, depending
        on the composition of a convoy. This is usually done in conjunction with
        the amendments of the dimension of the convoy. When the reference point
        is not set correctly, an offset of the actual position of the vessel might
        occur.</td>
    </tr>
  </tbody>
</table>

