# restful-api
difference between normal api n restful api

normal api's have got decorators
## @app.route('/',.....)
## def index():

Restful api use classes instead.

####class index(Resource):
####  def get(self):
######  return {'about': 'Hello World'}

routes are then declared for the specific class

api.add_resource(index, '/')
