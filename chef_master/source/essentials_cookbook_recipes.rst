=====================================================
Recipes
=====================================================

.. include:: ../../swaps/swap_desc_a.txt
.. include:: ../../swaps/swap_desc_b.txt
.. include:: ../../swaps/swap_desc_c.txt
.. include:: ../../swaps/swap_desc_d.txt
.. include:: ../../swaps/swap_desc_e.txt
.. include:: ../../swaps/swap_desc_f.txt
.. include:: ../../swaps/swap_desc_g.txt
.. include:: ../../swaps/swap_desc_h.txt
.. include:: ../../swaps/swap_desc_i.txt
.. include:: ../../swaps/swap_desc_j.txt
.. include:: ../../swaps/swap_desc_k.txt
.. include:: ../../swaps/swap_desc_l.txt
.. include:: ../../swaps/swap_desc_m.txt
.. include:: ../../swaps/swap_desc_n.txt
.. include:: ../../swaps/swap_desc_o.txt
.. include:: ../../swaps/swap_desc_p.txt
.. include:: ../../swaps/swap_desc_q.txt
.. include:: ../../swaps/swap_desc_r.txt
.. include:: ../../swaps/swap_desc_s.txt
.. include:: ../../swaps/swap_desc_t.txt
.. include:: ../../swaps/swap_desc_u.txt
.. include:: ../../swaps/swap_desc_v.txt
.. include:: ../../swaps/swap_desc_w.txt
.. include:: ../../swaps/swap_desc_x.txt
.. include:: ../../swaps/swap_desc_y.txt
.. include:: ../../swaps/swap_desc_z.txt
.. include:: ../../swaps/swap_http.txt
.. include:: ../../swaps/swap_names.txt
.. include:: ../../swaps/swap_notes.txt

.. include:: ../../includes_cookbooks/includes_cookbooks_recipe.rst

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Method
     - Description
   * - :doc:`essentials_cookbook_recipes_data_bags`
     - A data bag can be loaded by a recipe.
   * - :doc:`essentials_cookbook_recipes_search`
     - A search is a full-text query that can be done from several locations, including from within a recipe.
   * - :doc:`essentials_cookbook_recipes_use_ruby`
     - Anything that can be done with Ruby can be used within a recipe.
   * - :doc:`essentials_cookbook_recipes_in_recipes`
     - A recipe can include one (or more) recipes found in other cookbooks by using the ``include_recipe`` keyword.
   * - :doc:`essentials_cookbook_recipes_run_lists`
     - A recipe must be assigned to a run-list using the appropriate name, as defined by the cookbook directory and namespace.
   * - :doc:`essentials_cookbook_recipes_cookbook_dependencies`
     - If a cookbook has a dependency on a recipe that is located in another cookbook, that dependency must be declared in the |metadata rb| file for that cookbook using the ``depends`` keyword.
   * - :doc:`essentials_cookbook_recipes_handlers_and_logs`
     - A recipe can write events to a |chef| log file and can cause exceptions using ``Chef::Log``.
   * - :doc:`essentials_cookbook_recipes_tags`
     - A tag is a custom description that is applied to a node that can be helpful when building recipes by providing alternate methods of grouping similar types of information.

.. include:: ../../includes_cookbooks/includes_cookbooks_recipe_attribute.rst

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Method
     - Description
   * - :doc:`essentials_cookbook_recipes_attribute_types`
     - There are four types of attributes: ``default``, ``normal``, ``override``, and ``automatic``.
   * - :doc:`essentials_cookbook_recipes_attribute_persistence`
     - During a |chef| run, saved attributes are retrieved from the |chef server| and are merged with the attributes on the local system.
   * - :doc:`essentials_cookbook_recipes_attribute_precedence`
     - At the beginning of a |chef| run, all default, override, and automatic attributes are reset.
   * - :doc:`essentials_cookbook_recipes_attribute_automatic`
     - An automatic attribute is data that must be understood by |chef|, but not modified.
   * - :doc:`essentials_cookbook_recipes_attribute_notation`
     - Attributes are a special key-value store called a mash within the context of the |ruby| DSL.
   * - :doc:`essentials_cookbook_recipes_attribute_methods`
     - Methods are available to set attribute precedence in a cookbook.


.. toctree::
   :hidden:

   essentials_cookbook_recipes_data_bags
   essentials_cookbook_recipes_search
   essentials_cookbook_recipes_use_ruby
   essentials_cookbook_recipes_in_recipes
   essentials_cookbook_recipes_run_lists
   essentials_cookbook_recipes_cookbook_dependencies
   essentials_cookbook_recipes_handlers_and_logs
   essentials_cookbook_recipes_tags
   essentials_cookbook_recipes_attribute_types
   essentials_cookbook_recipes_attribute_persistence
   essentials_cookbook_recipes_attribute_precedence
   essentials_cookbook_recipes_attribute_automatic
   essentials_cookbook_recipes_attribute_notation
   essentials_cookbook_recipes_attribute_methods