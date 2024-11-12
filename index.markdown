---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h2 class="post-list-heading">Who is Mat?</h2>

```ruby
class Mat
    include Expertise::Advisor
    include Expertese::Cloud
    include Expertese::DevOps
    include Expertese::SoftwareDelivery
    include Experience::Developer
    include Experience::Engineer
    include Mentoring::Coach
    include Mentoring::Mentee
    include Mentoring::Mentor
    include Producer::ContentCreator
    include Hobbyist::DIY
    include Hobbyist::ElectronicsAndICs
    include Hobbyist::Microprocessors
    include Hobbyist::RenewableEnergy

    def self.contact()
        return {
            :email_work => 'mathew.dawe@460degrees.com',
            :email_hobby => 'engineeringmatdoes@gmail.com'
        }
    end

    def self.socials()
        return {
            :linked_in => 'https://www.linkedin.com/in/mathew-dawe',
            :youtube => 'https://www.youtube.com/@EngineeringMatDoes'
        }
    end

    def self.blog()
        return {
            :website => 'https://engineeringmatdoes.github.io/'
        }
    end
end
```
