===============================
apikeys.migrations.0001_initial
===============================

.. container:: wy-grid-for-nav

   .. container:: wy-side-scroll

      .. container:: wy-side-nav-search

         `ForensicVM <../../../index.html>`__

         .. container::

      .. container:: wy-menu wy-menu-vertical

         .. container:: local-toc

   .. container:: section wy-nav-content-wrap

      `ForensicVM <../../../index.html>`__

      .. container:: wy-nav-content

         .. container:: rst-content

            .. container::

               -  ` <../../../index.html>`__
               -  `Module code <../../index.html>`__
               -  apikeys.migrations.0001_initial
               -  

               --------------

            .. container:: document

               .. container::

                  .. rubric:: Source code for
                     apikeys.migrations.0001_initial
                     :name: source-code-for-apikeys.migrations.0001_initial

                  .. container:: highlight

                     ::

                        # Generated by Django 4.1.7 on 2023-05-01 15:32

                        from django.conf import settings
                        from django.db import migrations, models
                        import django.db.models.deletion


                        [docs]class Migration(migrations.Migration):

                            initial = True

                            dependencies = [
                                migrations.swappable_dependency(settings.AUTH_USER_MODEL),
                            ]

                            operations = [
                                migrations.CreateModel(
                                    name='ApiKey',
                                    fields=[
                                        ('id', models.BigAutoField(auto_created=True, primary_key=True, serialize=False, verbose_name='ID')),
                                        ('key', models.CharField(max_length=100, unique=True)),
                                        ('created_at', models.DateTimeField(auto_now_add=True)),
                                        ('user', models.ForeignKey(on_delete=django.db.models.deletion.CASCADE, to=settings.AUTH_USER_MODEL)),
                                    ],
                                ),
                            ]

            --------------

            .. container::

               © Copyright 2023, Nuno Mourinho.

            Built with `Sphinx <https://www.sphinx-doc.org/>`__ using a
            `theme <https://github.com/readthedocs/sphinx_rtd_theme>`__
            provided by `Read the Docs <https://readthedocs.org>`__.
