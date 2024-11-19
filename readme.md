<code>

DATABASES = {
    'default': {
        'ENGINE': 'djongo',
        'NAME': 'django_mongo',  
        'ENFORCE_SCHEMA': False,
        'CLIENT': {
            'host': "mongodb+srv://hbbadsha01:<your password>@cluster0.jhyzw.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0",
            'password': '<your password>',
        }
    }
}

</code>