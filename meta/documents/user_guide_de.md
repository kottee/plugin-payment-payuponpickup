# plentymarkets Payment – Barzahlung

Mit diesem Plugin binden Sie die Zahlungsart **Barzahlung** in Ihren Webshop ein.

## Zahlungsart einrichten

Bevor die Zahlungsart in Ihrem Webshop verfügbar ist, müssen Sie Einstellungen in Ihrem plentymarkets Backend vornehmen. Prüfen Sie zudem die Einstellungen für **Erlaubte Zahlungsarten** in den <strong><a href="https://knowledge.plentymarkets.com/auftragsabwicklung/payment/zahlungsarten-verwalten#30" target="_blank">Kundenklassen</a></strong> und für **Gesperrte Zahlungsarten** in den <strong><a href="https://knowledge.plentymarkets.com/auftragsabwicklung/fulfillment/versand-vorbereiten#1000" target="_blank">Versandprofilen</a></strong>.

##### Zahlungsart einrichten:

1. Öffnen Sie das Menü **System&nbsp;» Aufträge&nbsp;» Zahlung » Plugins » Barzahlung**.
2. Wählen Sie einen Mandanten.
3. Nehmen Sie die Einstellungen vor. Beachten Sie dazu die Erläuterungen in Tabelle 1.
4. **Speichern** Sie die Einstellungen.

<table>
<caption>Tab. 1: Einstellungen für die Zahlungsart vornehmen</caption>
	<thead>
		<th>
			Einstellung
		</th>
		<th>
			Erläuterung
		</th>
	</thead>
	<tbody>
        <tr>
			<td>
				<b>Sprache</b>
			</td>
			<td>
				Sprache wählen. Die übrigen Einstellungen, z.B. Name, Infoseite etc., werden sprachabhängig gespeichert.
			</td>
		</tr>
        <tr>
			<td>
				<b>Name</b>
			</td>
			<td>
				Die Bezeichnung, die in der Übersicht der Zahlungsarten in der Kaufabwicklung für diese Zahlungsart angezeigt wird.
			</td>
		</tr>
		<tr>
			<td>
				<b>Infoseite</b>
			</td>
			<td>Wählen, ob als <a href="https://knowledge.plentymarkets.com/auftragsabwicklung/payment/bankdaten-verwalten#40"><strong>Information zur Zahlungsart</strong></a> eine Kategorieseite oder eine externe Webseite angezeigt wird.
			</td>
		</tr>
		<tr>
			<td>
				<b>Infoseite intern/<br />Infoseite extern</b>
			</td>
			<td>In der Beschreibung der Zahlungsart wird ein Link zu den <strong>Details</strong> der Zahlungsart angezeigt.<br /><strong>Infoseite intern:</strong> Über Eingabe der Kategorie-ID oder das Auswahlfeld eine Kategorieseite vom Typ <strong>Content</strong> wählen, die weitere Informationen zur Zahlungsart bietet.<br /><strong>Infoseite extern:</strong> Die URL einer externen Informationsseite eingeben. <strong><i>Wichtig:</i></strong>Entweder http:// oder https:// verwenden.<br />Wird keine Eingabe vorgenommen, wird kein Link angezeigt.
			</td>
        <tr>
			<td>
				<b>Logo</b>
			</td>
			<td>
			Wählen, ob das im Plugin hinterlegte <strong>Standard-Logo</strong> der Zahlungsart oder ein eigenes Logo angezeigt wird.
			</td>
		</tr>
        <tr>
			<td>
				<b>Logo-URL</b>
			</td>
			<td>
			Eine https-URL, die zum Logo-Bild führt. Gültige Dateiformate sind .gif, .jpg oder .png. Die Maximalgröße beträgt 190 Pixel in der Breite und 60 Pixel in der Höhe.
			</td>
		</tr>
		<tr>
			<td>
				<b>Beschreibung</b>
			</td>
			<td>
				Eine Beschreibung der Zahlungsart eingeben, die dem Kunden in der Kaufabwicklung angezeigt wird. Der Text wird nach 150 Zeichen mit Ellipse abgeschnitten.
			</td>
		</tr>
		<tr>
			<td>
				<b>Lieferländer</b>
			</td>
			<td>
				Nur für die hier eingestellten Lieferländer ist diese Zahlungsart freigegeben.
			</td>
		</tr>
	</tbody>
</table>

## Logo der Zahlungsart auf der Startseite anzeigen

Das Template-Plugin **Ceres** bietet Ihnen auf der Startseite einen Template-Container, in dem Sie die Logos Ihrer Zahlungsart anzeigen können. Gehen Sie wie im Folgenden beschrieben vor, um das Logo der Zahlungsart zu verknüpfen.

##### Logo mit Template-Container verknüpfen:

1. Gehen Sie zu **Plugins » Content**.
3. Wählen Sie den Bereich **Pay upon pickup icon**.
4. Aktivieren Sie den Container **Homepage: Payment method container**.
5. **Speichern** Sie die Einstellungen.<br />→ Das Logo der Zahlungsart wird auf der Startseite des Webshops angezeigt.

## Lizenz

Das gesamte Projekt unterliegt der GNU AFFERO GENERAL PUBLIC LICENSE – weitere Informationen finden Sie in der [LICENSE.md](https://github.com/plentymarkets/plugin-payment-payuponpickup/blob/master/LICENSE.md).
