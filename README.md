# A Curated List of Development and Deployment Tools for Computer Vision Projects in Python

---

## Table of Contents

- [Deep Learning Frameworks](#deep-learning-frameworks)
- [Data Augmentation Frameworks](#data-augmentation-frameworks)
- [Machine Learning Management and Experimentation](#machine-learning-management-and-experimentation)
- [Container Management](#container-management)
- [Cloud Computing Service Providers](#cloud-computing-service-providers)
- [Cheap GPU Training Providers](#cheap-gpu-training-providers)
- [Storage](#storage)
- [API Tools](#api-tools)
- [Application Development](#application-development)
- [Web Hosting Platforms](#web-hosting-platforms)
- [Application Testing](#application-testing)
- [Continuous Integration (CI) and Continuous Deployment (CD)](#continuous-integration-ci-and-continuous-deployment-cd)
- [Error Monitoring Tools](#error-monitoring-tools)
- [Miscellaneous](#miscellaneous)

---

## Deep Learning Frameworks

- PyTorch: [[Website](https://pytorch.org)] *(recommended)*
- TensorFlow: [[Website](https://www.tensorflow.org)]
- Keras: [[Website](https://keras.io)]
- Theano: [[Website](https://github.com/Theano/Theano)] *(discontinued)*
- Caffe: [[Website](https://caffe.berkeleyvision.org)] *(discontinued)*

---

## Data Augmentation Frameworks

- albumentations: [[Website](https://albumentations.ai)] *(recommended)*
- imgaug: [[Website](https://imgaug.readthedocs.io/en/latest/)]
- augmentor: [[Website](https://augmentor.readthedocs.io/en/master/)]

---

## Machine Learning Management and Experimentation

- Airflow `Workflow Orchestration`: [[Website](https://airflow.apache.org)] | [[Github](https://github.com/apache/airflow)] *(recommended for commercial use)*
- Prefect `Workflow Orchestration`: [[Website](https://www.prefect.io)] | [[Github](https://github.com/PrefectHQ/prefect)]
- Dagster `Workflow Orchestration`: [[Website](https://dagster.io/)] | [[Github](https://github.com/dagster-io/dagster)]
- Luigi `Workflow Orchestration`: [[Github](https://github.com/spotify/luigi)]
- Flyte `Workflow Orchestration`: [[Website](https://flyte.org)] | [[Github](https://github.com/flyteorg/flyte)] *(recommended for Kubernetes use)*
- Metaflow `Workflow Orchestration`: [[Website](https://metaflow.org)] | [[Github](https://github.com/Netflix/metaflow)] *(recommended for AWS use)*
- Ploomber `Workflow Orchestration`: [[Website](https://docs.ploomber.io/en/latest/)] | [[Github](https://github.com/ploomber/ploomber)] *(recommended for notebook use)*
- NiFi `Workflow Orchestration`: [[Website](https://nifi.apache.org)] | [[Github](https://github.com/apache/nifi)]
- TensorFlow Extended (TFX) `Workflow Orchestration`: [[Website](https://tensorflow.github.io/tfx/)] | [[Github](https://github.com/tensorflow/tfx)]
- MLflow `Experiment Tracking & Management`: [[Website](https://mlflow.org)] |[[Github](https://github.com/mlflow/mlflow)] *(recommended for commercial use)*
- WandB `Experiment Tracking & Management`: [[Website](https://wandb.ai)] | [[Github](https://github.com/wandb/wandb)] *(recommended for personal & academic use)*
- neptune ai `Experiment Tracking & Management`: [[Website](https://neptune.ai)] |[[Github](https://github.com/neptune-ai/neptune-client)]
- ClearML `Experiment Tracking & Management`: [[Website](https://clear.ml)] | [[Github](https://github.com/clearml/clearml)]
- TensorBoard `Experiment Tracking & Management`: [[Website](https://www.tensorflow.org/tensorboard)] | [[Github](https://github.com/tensorflow/tensorboard)]
- DVC `Data Versioning`: [[Website](https://dvc.org)] | [[Github](https://github.com/iterative/dvc)]

---

## Container Management

- Docker: [[Website](https://www.docker.com)] *(recommended)*
- Kubernetes: [[Website](https://kubernetes.io)] *(recommended)*
- Incus: [[github](https://github.com/lxc/incus)]
- Podman: [[github](https://github.com/containers/podman)]
- Buildah: [[github](https://github.com/containers/buildah)]

---

## Cloud Computing Service Providers

- AWS: [[Website](https://aws.amazon.com)] *(recommended)*
- GCP: [[Website](https://cloud.google.com)]
- Azure: [[Website](https://azure.microsoft.com/)]

---

## Cheap GPU Training Providers

- Vast AI: [[Website](https://vast.ai)] *(recommended)*
- Colab Pro: [[Website](https://colab.research.google.com/signup)] *(recommended)*
- Paperspace: [[Website](https://www.paperspace.com)]
- Lambda: [[Website](https://lambdalabs.com/service/gpu-cloud/1-click-clusters)]
- RunPod: [[Website](https://www.runpod.io)]

---

## Storage

- MongoDB `NoSQL`: [[Website](https://www.mongodb.com)] *(recommended)*
- Cassandra `NoSQL`: [[Website](https://cassandra.apache.org/)]
- MySQL `SQL`: [[Website](https://www.mysql.com)]
- PostgreSQL `SQL`: [[Website](https://www.postgresql.org)] *(recommended)*
- Oracle `SQL`: [[Website](https://www.oracle.com/database/)]
- Redis `In-Memory`: [[Website](https://redis.io)] *(recommended)*
- Memcached `In-Memory`: [[Website](https://memcached.org)]
- Kafka `Distributed Streaming`: [[Website](https://kafka.apache.org)]

---

## API Tools

- Postman: [[Website](https://www.postman.com)] *(recommended)*
- Thunder Client: [[Website](https://www.thunderclient.com)]
- Insomnia: [[Website](https://insomnia.rest)]
- Testfully: [[Website](https://testfully.io)]

---

## Application Development

- Gradio: [[Website](http://www.gradio.app/)], [[github](https://github.com/gradio-app/gradio)] (recommended)
- Streamlit: [[Website](https://streamlit.io)], [[github](https://github.com/streamlit/streamlit)]
- Dash: [[Website](https://plotly.com/dash)], [[github](https://github.com/plotly/dash)]
- Panel: [[Website](https://panel.holoviz.org/)], [[github](https://github.com/holoviz/panel)]
- Voila: [[Website](https://voila.readthedocs.io/)], [[github](https://github.com/voila-dashboards/voila)]
- Autogluon: [[Website](https://auto.gluon.ai/)], [[github](https://github.com/autogluon/autogluon)]

---

## Web Hosting Platforms

- HF Spaces: [[Website](https://huggingface.co/spaces)]
- Vercel: [[Website](https://vercel.com)]
- Heroku: [[Website](https://www.heroku.com)]
- Render: [[Website](https://render.com)]
- DigitalOcean: [[Website](https://www.digitalocean.com)]

---

## Application Testing

- axe DevTools `web`: [[Chrome Extension](https://chromewebstore.google.com/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)] | [[Github](https://github.com/dequelabs/axe-core)]
- WAVE Evaluation Tool `web`: [[Chrome Extension](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)] | [[Website](https://wave.webaim.org)]
- Lighthouse `web | desktop`: [[Chrome Extension](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk)] | [[Github](https://github.com/GoogleChrome/lighthouse)]
- Appium `mobile | web | desktop`: [[Wesbite](http://appium.io)] | [[Github](https://github.com/appium/appium)]
- Playwright `web`:  [[Wesbite](https://playwright.dev)] | [[Github](https://github.com/microsoft/playwright)]
- Maestro `mobile | web`: [[Wesbite](https://www.maestro.dev)] | [[Github](https://github.com/mobile-dev-inc/Maestro)]
- flashlight `mobile`: [[Wesbite](https://docs.flashlight.dev/)] | [[Github](https://github.com/bamlab/flashlight)]

---

## Continuous Integration (CI) and Continuous Deployment (CD)

- Jenkins: [[Wesbite](https://www.jenkins.io/)] | [[Github](https://github.com/jenkinsci/jenkins)]
- CircleCI: [[Wesbite](https://circleci.com/)]
- Travis CI: [[Wesbite](https://travis-ci.org/)] | [[Github](https://github.com/travis-ci/travis-ci)]
- GitHub Actions: [[Wesbite](https://github.com/features/actions)]

---

## Error Monitoring Tools

- Sentry: [[Website](https://sentry.io/)], [[github](https://github.com/getsentry/sentry)]
- Loguru: [[github](https://github.com/Delgan/loguru)]
- Countly: [[Website](https://countly.com/)], [[github](https://github.com/Countly/countly-server)]
- stackprinter: [[github](https://github.com/cknd/stackprinter  )]

---

## Miscellaneous

- Building interactive python code validation over webpages/LMS
  - [PyScript](https://github.com/pyscript/pyscript)
  - [DataCamp Light](https://github.com/datacamp/datacamp-light)
  - [CodeRunner -- Moodle Plugin](https://coderunner.org.nz)
  - [VPL -- Moodle Plugin](https://vpl.dis.ulpgc.es)
- Integrated Development Environments (IDEs)
  - VSCode: [[Website](https://code.visualstudio.com)] *(recommended)*
  - PyCharm: [[Website](https://www.jetbrains.com/pycharm/)]
  - Eclipse: [[Website](https://www.eclipse.org)]
- Remote Desktop Tools
  - RustDesk: [[Website](https://rustdesk.com)] [[Github](https://github.com/rustdesk/rustdesk)] *(recommended)*
  - Chrome Remote Desktop: [[Website](https://remotedesktop.google.com)]
  - AnyDesk: [[Website](https://anydesk.com/)]
  - TeamViewer: [[Website](https://www.teamviewer.com/)]
- Python environment / package managers
  - pip: [[Website](https://pypi.org)] | [[GitHub](https://github.com/pypa/pip)]
  - pipenv + pyenv: [[Website-pipenv](https://pipenv.pypa.io/en/latest/)] | [[GitHub-pipenv](https://github.com/pypa/pipenv)] | [[Github-pyenv](https://github.com/pyenv/pyenv)] *(recommended)*
  - Poetry: [[Website](https://python-poetry.org/)] | [[GitHub](https://github.com/python-poetry/poetry)]
  - Conda + mamba: [[Website-Conda](https://docs.conda.io/projects/conda/)] | [[Website-mamba](https://mamba.readthedocs.io/)] | [[GitHub-Conda](https://github.com/conda/conda)] | [[GitHub-mamba](https://github.com/mamba-org/mamba)] 
  - uv: [[Website](https://docs.astral.sh/uv)] | [[GitHub](https://github.com/astral-sh/uv)] *(recommended)*
- Data Serialization Formats
  - `JSON`: Fast for parsing, used for API communications and web applications.
  - `YAML`: Human-readable format, used for DevOps purposes (i.e. Docker Compose).
  - `XML`: Used for document storage and web services (i.e. SOAP).
- File Data Storage Formats
  - `CSV`: Ideal for structured tabular data that requires a human-readable format.
  - `JSON`: Best for storing hierarchical data, such as API responses and configurations.
  - `H5Py`: Designed for large scientific datasets that require efficient storage and retrieval.
  - `Pickle`: Used for saving and loading Python objects, but avoid for long-term storage due to limited cross-language support (Python-only).
  - `NumPy`: Optimized for fast and efficient storage of numerical data, particularly arrays.
  - `Optimized Row Columnar (ORC)`: Suitable for streaming large data with cross-language support.
  - `Parquet`: Used for faster storage in a columnar format. *(recommended instead of `NumPy`)*
  - `MessagePack`: Provides compact and fast serialization for large structured data, with support for streaming without compression. *(recommended instead of `Pickle`)*
