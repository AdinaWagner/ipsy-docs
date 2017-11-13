Backups
*******

All data located under the ``/home/`` directory are snapshot at 07:00 every day.
*Except* for any data located in ``/home/<user_name>/scratch/`` or
``/home/data/<project_name>/scratch/`` folders. These snapshots are then
transferred to a dedicated backup server located in a different building on the
OvGU campus.

The backup retention policy is:

* daily backups kept for 2 weeks
* weekly backups kept for 6 weeks
* monthly backups kept for 1 year
* yearly backups kept for 2.5 years

  * except for ``/home/data/archive``, for which yearly backups are kept "forever"

If you need to have data recovered from a backup, contact Alex and he will help
recover your data.
