---
layout: page
title: "<b> Sahayak</b>"
description: "<b>An Intelligent AI Health Assistant</b>"
img: /assets/img/sahayak.jpeg
importance: 1
---

A sophisticated implementation of RASA Conversational AI on a HealthCare Bot integrated with a Web and Android Software written in Python, Java and JavaScript. This conversational AI provides the user a self-assessment to the recent Covid-19 based on user symptoms- all in a conversational pattern, while the webapp provides a complete Hospital Management System along with the essential health related informations.

This project and the research work were successfully accredited by the conference ICCSEA at GIET University, India. The research work is publicly available in [IEEE](https://ieeexplore.ieee.org/document/9936169).


<div class="row">
    <div class="col-sm mt-3 mt-md-0 d-flex justify-content-center align-items-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sahayak.jpeg' | relative_url }}" alt="" title="example image" style="max-height: 700px;" />
    </div>
</div>

<div class="caption">
    Sahayak Health Web-App. A complete Hospital Management System along with the essential health related informations.
</div>

This system implements RASA chatbot as its main module for text-based prompt assistance service to the patients. The chatbot helps the patients for booking/maintaining their appointments, and also provides the patients with the essential health related informations. Built with the RASA version 2.0, the chatbot is also integrated with a webapp and an android app. The webapp provides a complete Hospital Management System along with the essential health related informations. The android app provides the patients with the essential health related informations and also helps them to book/maintain their appointments.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 d-flex justify-content-center align-items-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sahayak_doctors.jpeg' | relative_url }}" alt="" title="example image" style="max-height: 550px;" />
    </div>
</div>


<div class="caption">
    An image of the Doctors' Dashboard.
</div>
Figures below demonstrate the flexibility and user-accessibility of the system. The frontend was built wit <b>React Native </b> with proper consideration of patients' ease of use. The backend was built with <b>Django and Django Rest Framework.</b> The chatbot was built with <b>RASA</b> and the NLU model was trained with the help of the RASA X. The chatbot was deployed on the server with the help of <b>Docker and Docker Compose.</b> The chatbot was integrated with the frontend with the help of the RASA REST API. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ 'assets/img/sahayak_appointment_dark.jpeg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sahayak_userprofile.jpeg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

<div class="caption">
    Some images of the features related to Hospital Appointment Booking and User Profile.
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sahayak_chatbot_workflow.png' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Sahayak_workflow.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Workflow of the RASA Chatbot <i>(left)</i> and the Sahayak Health System <i>(right)</i>.
</div>

This project is open-sourced under the GNU General Public License. You can find the source code of the project in [GitHub](https://github.com/bishab/Sahayak-Health).

