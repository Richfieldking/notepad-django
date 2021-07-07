# notepad-django
Models(
    title,
    image[blank=True],
    url[blank=True],
    timestamp[autonowadd]

    __str__[return title]
    get_absoulute_url[refer to the link of an instance of this model]/notes/{}.format(self.pk)

    r{'notes/', self.pk}

    get_delete_url[return to the link of the particular note to be deleted /notes/{}/delete, self.pk]

    get_delete_url[return to the link of the particular note to be updated /notes/{}/update, self.pk]

Add a user model to the note models by importing settings from django.conf



)