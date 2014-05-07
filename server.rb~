require 'sinatra'
require './expense'

expenses = []

get '/' do
	@expenses = expenses
	erb :index
end

get '/new' do
	erb :new
end

post '/save' do
	redirect to '/'
end

get '/show/:id' do
	erb :show
end
