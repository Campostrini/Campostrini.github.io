---
layout: single
title: Projects
permalink: /projects/
---

Projects, who doesn't like them? Unfortunately some of them are not easy to takle alone. This list is a loose collections of projects I would love to collaborate on or things that I have done. Maybe I will use Jekyll Posts or do separate pages in the future. Shoot me an email if you find any of them interesting.

### Precipitation Nowcasting with Deep Learning

For my MSc Thesis I developed a UNet with Pytorch and Pytorch-Ligthning that forecasts the precipitation distribution over northern Germany 1h in advance. It uses the German Weather Service's 1h-cumulative precipitation data from the RADOLAN Routine at t-5h, t-4h, t-3h, t-2h, t-1h, t. The output is for t+1h.

You can read the thesis [here](https://diglib.uibk.ac.at/ulbtirolhs/content/titleinfo/7782855) and find the code [here](https://github.com/Campostrini/dwd_dl)

### ECG VFib Alarm

Ventricular fibrillation (VFib) is a dangerous arrhitmia. Patients at risk have a (Subcutaneus-)Implantable Cardioverter Defibrillator (S-ICD) or use a Wearable Cardioverter Defibrillator (WCD). After a Miocardial Infarction (MI) the risk of VFib is increased, however this doesn't necessarily lead to the implantation of an ICD.

Idea: use an ECG patch for constant patient telemetry and have an alarm sound for family members if a dangerous arrhythmia is detected. Obviously there needs to be an Automatic External Defibrillater (AED) in the immediate vicinities for this to have sense.
