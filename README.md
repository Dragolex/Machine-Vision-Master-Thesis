# Machine Vision for Industrial Robot Systems
## Abstraction and Implementation for ”drag & bot”

  
  
##### Abstract

This work proposes and validates a hardware-independent interface for industrial machine vision systems. The proposed interface and methods allow to integrate computer vision applications using diﬀerent hardware, camera positions and software modules in a common way increasing the compatibility, the ease of use and reducing the integration cost. The interface was validated through the ROS (Robot Operating System) based robot programming framework drag & bot showing diﬀerent real industrial-relevant examples.

This work ﬁrst analyses the diﬀerences between the existing machine vision and the state of art solutions nowadays including diﬀerent types of cameras and positions. The focus lies on the company’s goals to achieve software that is extendable and reusable.

Then in the main part, the interface and related methods are proposed covering all processes needed for conﬁguring the machine vision system such as for example camera calibration. Finally it describes the implementation of the interface including diﬀerent prototypes, a ”sequence system” that minimizes work required at modifying or expanding functionality. The paper closes with a reevaluation of the ﬁnal results, taking the initial goals into account and focusing on the conclusions obtained. Furthermore, an outlook to the future of machine vision for drag & bot is provided.

The conclusion that the interface fulﬁlls the requirements resulted in inclusion of the interfaces in the drag & bot software as part of the internal functionality.

  
##### Zusammenfassung

Diese Arbeit schlägt ein machine vision Interface für das Industrieroboter Kontrollsystem drag & bot vor und begründet es. Das Interface hat zum Ziel hardwareunabhängig zu sein und Ziele der, betreuenden Firma wie Widerverwendbarkeit und Erweiterbarkeit zu erfüllen. Diese werden mit analysierten Lösungen auf dem Stand der Technik mit Fokus auf verschiedenen Kamera-Arten und Nutzer-Anwendungen verglichen.

Der Hauptteil befasst sich mit dem Design und Implementation eines Interfaces für SmartCamera welches Robot Operating System (ROS) - Services einsetzt um die interne Kommunikation abzukapseln. Des weiteren wird die Entwicklung einer Kamera-zu-Roboter Kalibrierung beschrieben welche darüuber hinaus ein universelles Sequenz-basiertes Interface umfasst welches den Implementationsaufwand reduziert.

Schlussendlich wird die resultierende Software, insbesondere im Einsatz in Demonstrations Aufbauten analysiert und hinsichtlich der Zielvorgabe verglichen. Das Resultat is dass das Interface ihren Zweck für die drag & bot GmbH mit den momentan vorliegenden Hardwarekomponenten erfüllt.
