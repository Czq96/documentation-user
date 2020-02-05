===========================
Get Started with Timesheets
===========================
Become able to track the time spent on tasks, from any device, anywhere, and compare a forecasted
time with the real one.

Choose an encoding unit
=======================
Under :menuselection:`Configuration --> Settings` choose the unit of measure used to register
your timesheet.
This will provide tools and widgets to help you encoding.

*Minimal duration* is the minimum time at which a task will be recorded.

*Rounding up* allows you to time up or down to the nearest minutes or hours. For example: if the
interval is set to 30min, a 14min entry will show up in reports as 0min, and a 29min entry
as 30mi.


.. image:: media/get1.png
   :align: center
   :alt: Encoding Units in Odoo Timesheets application


.. note::
   Reportings will be expressed in hours - the default value.


Create a task from a sales order & timesheet on it
===================================================
Under the *General Settings* of your product, categorize it as a service.

On the *Sales* tab, choose if you want to invoice customers based on the quantity previously ordered
(the one sent on a quotation, for instance), on the time recorded while the service was happening,
or by manually adding the time spent when creating the invoice.

Chose the right *Service Tracking* for you, and from now on, when a sales order is confirmed,
Odoo will automatically create a task/project (if that was the option chosen) and allow you to
timesheet on it.


.. image:: media/get2.png
   :align: center
   :alt: Create a task and timesheet from a Sales Order in Odoo Timesheets application


Choose an Invoicing Policy
==========================
Go to :menuselection:`Configuration --> Settings` and choose if you want the recorded time
to be directly invoiced, or if it should be approved first.


.. image:: media/get3.png
   :align: center
   :alt: Invoicing Policy in Odoo Timesheets application


Send reminders
==============
Choose to have an automatic email been sent to all users and managers who have not recorded their
time.
Go to :menuselection:`Configuration --> Settings` and enable the *Employee Reminder* and
*Manager Reminder* features.


.. image:: media/get4.png
   :align: center
   :alt: Remind Users and Employees in Odoo Timesheets application


.. tip::
   Odoo Timesheets continues to run even if there is no internet connection. The data syncs once you
   are back online.
