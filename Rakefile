namespace :framework do
	task :get do
		sh "go get github.com/nicholasjackson/go-mobile-framework"
	end

	task :build do
		sh "#{ENV['GOPATH']}/bin/gomobile bind -target=android -o ./GoMobileAndroid/app/libs/mobilesdk.aar github.com/nicholasjackson/go-mobile-framework"
	end
end
