# Anwendung für Bankenn

Ein virtueller Geldbeutel braucht eine kleine Anwendung, an der Benutzer Bankkonten beim verschiedenen Banken erstellen können.

Jeder Benutzer hat ein CNP, einen Namen, eine boolesche Variable, um zu sehen, ob sie für einen Kreditkonto kompatibel ist oder nicht, eine Liste der erstellten Konten und eine Liste der beantragten Darlehen, beide mit dem entschprechenden Banken.

Jede Bank hat einen Namen, die Kapitalkraft der Bank (den Gesamtbetrag, der bei einer Bank eingezahlt wurde) eine Liste von Benutzern, eine Liste von Währungen und eine Liste der Darlehen für jeder Benutzer, der sich für ein Darlehen entschieden hat.

Jedes Darlehen hat eine Darlehnszinsen, einen geliehener Geldbetrag, einen Geldbetrag der noch bezahlt werden muss und einen Fälligkeitstermin.

Jedes Konto hat einen Benutzer, ein IBAN, einen aktuellen Geldbetrag und ein Verfallsdatum. Darüber hinaus, kann ein Konto von zwei Arten sein, Debit und Kredit. Jedes Kreditkonto hat eine Liste von Raten, eine boolesche Variable, um zu prüfen ob das Kreditkonto aktiv oder nicht ist und einer zulässiger minimaler Geldbetrag, den der aktuelle Saldo erreichen kann. (sobald diese zulässige Summe überschritten wird, wird das Kreditkonto geschlossen).

Ein Debitkonto benutzt eine Währung, die einen Namen und einen Wechselkurs hat.

1.	Die Anwendung ermöglicht es den Benutzern, ein Konto bei einer Bank ihrer Wahl, oder bei mehrere Banken, zu registrieren. Wenn ein User nicht kompatibel für ein Kreditkonto ist, dann wird die Bank das erstellen so eines Konto nicht erlauben. Ein Benutzer ist nicht mehr mit einem solchen Konto kompatibel, wenn er den Mindestbetrag für ein älteres Kreditkonto überschritten hat.

2.	Die Anwendung ermöglicht auch die Schließung von Konten auf Wunsch der Benutzer oder bei Ablauf der Konto.

3.	Mit der Anwendung können Banken ihren Wechselkursen täglich aktualisieren.

4.	Die Anwendung ermöglicht die Eröffnung eines Darlehensfonds auf Wunsch des Benutzers mit dem von ihm angeforderten Betrag.

5.	Die Anwendung ermöglicht die Zahlung eines vom Benutzer gewählten Betrags für ein Darlehen bei einer Bank. Die Auszahlung eines Darlehens wird innerhalb der Anwendung in Abhängigkeit von den von der Bank auferlegeten Zinsen und dem vom Benutzer geliehenen Betrag berechnet. Nach der Zahlung wird der zu zahlende Restbetrag aktualisiert.

6.	Diese Anwendung ermöglicht auch den Benutzern die Kapitalkraft einer Bank zu sehen.

7.	In Bezug auf Konten, ermöglicht die Anwendung die folgende:

    I.	Einzahlung von Geld auf Konto.

    II.	Auszahlung von Geld vom Konto.

    III.	Die Anzeige der Zahlungshistorie und des Geldeingangs.

    IV.	Die Anzeige des aktuellen Saldos.

    V.	Beim Debitkonten, ermöglicht diese Anwendung die folgende:


         a.	Der Umtausch eines gewünschten Geldbetrags, abhängig vom von der Bank bestellten Wechselkurs.
         b.	Die Überweisung eines gewünschten Geldbetrags an einen anderen Benutzer.
 
    VI.	Beim Kreditkonten, ermöglicht diese Anwendung die folgende:

        a.	Hinfügen einer neuer Rate.
        b.	Anzeigen einer Liste von Raten die noch aktiv sind.
        c.	Anzeige des Gesamtzahlungsbetrags für Raten.
        d.	Die tatsächliche Zahlung der Raten in einem Monat.


## Diagramm
![App Screenshot](https://i.imgur.com/yp4FnBk.jpeg)