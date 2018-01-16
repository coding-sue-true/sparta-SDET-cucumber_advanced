# sparta-SDET-cucumber_advanced


capybara gem
cucumber gem
pry gem
rspec gem


Then(/^I receive the corresponding error (.*)$/) do |error_message|
  expect(bbc_register_page.check_error_message).to eq error_message
end
