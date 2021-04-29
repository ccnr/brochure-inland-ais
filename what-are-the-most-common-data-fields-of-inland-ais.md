# What are the most common data fields of Inland AIS?

It is very important to ensure that Inland AIS is used correctly and that the transmitted data are correct and up-to-date. Therefore, this page will give some hints for the skipper and explains \(when applicable\) for what reasons the data are used. For the daily operations, the skipper can also make use of the [checklist](voyage-checklist.md).

{% page-ref page="how-to-enter-my-voyage-data-in-the-inland-ais-device.md" %}

{% page-ref page="which-data-is-transmitted-by-the-ais-device.md" %}

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
      <td style="text-align:left">The MMSI number is the identity number of the transmitting AIS station
        and is assigned by the competent telecommunication administration and for
        on-board radio communication equipment. The assigned MMSI number is set
        by the specialized approved firm when installing the Inland AIS device.
        This number helps the authorities&apos; vessel traffic management systems
        to identify a vessel and connect it to current voyage data.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Name of the vessel</b>
      </td>
      <td style="text-align:left">
        <p>The name of the vessel is set by the specialized approved firm when installing
          the Inland AIS device. The name of the vessel helps the skipper to identify
          traffic in the vicinity and in case of VHF communication he / she can call
          the vessels name directly.</p>
        <p>The vessel traffic management systems of the authorities use the name
          of the vessel to identify the vessel (show the name of the vessel on a
          map or shore-based radar systems (VTS).</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Vessel or convoy type</b>
      </td>
      <td style="text-align:left">The <a href="how-to-set-a-convoy-or-a-towed-convoy-in-the-inland-ais-device.md"><em>vessel or convoy type</em></a> is
        used by vessel traffic management systems of the authorities in order to
        identify the composition of a convoy and/or to plan lock cycles. Inland
        AIS provides a list of different vessel and convoy types to choose from.
        For a single vessel, the vessel type will be set during installation. For
        a convoy, the convoy type may change for each vessel depending on the number
        and type of the coupled barges. This needs to be updated by the skipper
        for each voyage.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>ENI number</b>
      </td>
      <td style="text-align:left">The ENI number is the European inland navigation vessel number. It is
        set by the specialized approved firm when installing the Inland AIS device.
        The ENI number is used by vessel traffic management systems of the authorities
        to identify vessels and connect them to their current voyage data.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Dimensions</b>
      </td>
      <td style="text-align:left">
        <p>The dimensions are the overall length and beam of the vessel or convoy.
          For a single vessel, those values are set by the specialized approved firm
          during installation of the Inland AIS station. For a convoy the values
          must be set by the skipper according to the actual situation of the convoy.
          The skipper uses the dimensions of other vessels so as to ensure safe passing
          and overtaking.</p>
        <p>The authorities use the dimensions in their vessel traffic management
          systems for lock planning and/or VTS services</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Position</b>
      </td>
      <td style="text-align:left">The position is used for displaying the vessel on a map. This position
        information of a vessel reflects the actual position of the Inland AIS
        station&#x2019;s GPS antenna on board of the vessel. The position is used
        by other skippers and authorities.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Speed over ground</b>
      </td>
      <td style="text-align:left">
        <p>The speed over ground is transmitted automatically by the Inland AIS device.
          The skipper uses the speed to identify if a vessel is moving and at what
          speed.</p>
        <p>The vessel traffic management systems of authorities use the speed over
          ground to identify if a vessel is moving in order to display the vessel
          in the list of &quot;vessels underway&quot; or the list of &quot;vessels
          moored/waiting&quot;.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Course</b>
      </td>
      <td style="text-align:left">The course of the vessel is transmitted automatically by the Inland AIS
        device. It is used by the skipper and the authorities to determine the
        sailing direction of a vessel.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Navigational status</b>
      </td>
      <td style="text-align:left">The navigational status gives an indication about the operation status
        of the vessel (e.g. &#x2018;underway using engine&#x2019;, &#x2018;at anchor&#x2019;,
        &#x2018;moored&#x2019;) and is set by the skipper (or automatically in
        combination with an Inland ECDIS system). The vessel traffic management
        systems of the authorities use this information for planning purposes.
        The navigational status might not be so important for the skipper, but
        to be informed that an Inland AIS device that is transmitting &#x2018;Underway,
        using engine&#x2019; claims far more time-slots for transmitting in contrast
        to the navigational status &#x2018;Moored&#x2019;. In dense areas especially
        (such as ports) it helps to reduce the load to the system if the navigational
        status is set to &#x2018;Moored&#x2019; when a vessel is moored. The navigational
        status is set by the skipper but some suppliers (Inland ECDIS) offer the
        feature of an (semi)automatic setting of the navigational status based
        on the speed over ground. Check with your Inland ECDIS supplier what the
        possibilities are.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Reference point</b>
      </td>
      <td style="text-align:left">The reference point of the vessel is in most cases the position of the
        AIS station&#x2019;s GPS antenna. The reference point is set by the specialized
        approved firm during installation of the Inland AIS station. Only in the
        case of convoys does the reference point need to be changed, depending
        on the composition of a convoy. This is usually done in conjunction with
        the amendments of the dimension of the convoy. When the reference point
        is not set correctly, an offset of the actual position of the vessel might
        occur.</td>
    </tr>
  </tbody>
</table>

