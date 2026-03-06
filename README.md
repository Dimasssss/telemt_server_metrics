# Server Metrics 2026-03-06 15:19:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 17877.5 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528976
telemt_connections_bad_total 4508
telemt_handshake_timeouts_total 2750
telemt_upstream_connect_attempt_total 9102
telemt_upstream_connect_success_total 9044
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 1862
telemt_me_reconnect_success_total 1851
telemt_me_reader_eof_total 1947
telemt_me_idle_close_by_peer_total 1947
telemt_me_route_drop_no_conn_total 190374
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2838
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 2144
telemt_desync_frames_bucket_total{bucket="1_2"} 677
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 1207
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1949
telemt_me_writer_restored_same_endpoint_total 1845
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 453763
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 11650039240 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 179530765144 (167.20 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 17877.3 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202510
telemt_connections_bad_total 860
telemt_handshake_timeouts_total 6299
telemt_upstream_connect_attempt_total 8622
telemt_upstream_connect_success_total 8602
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 879
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 101456
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 717
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 186453
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 2096927032 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 80951923396 (75.39 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 17877.4 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406024
telemt_connections_bad_total 5288
telemt_handshake_timeouts_total 37331
telemt_upstream_connect_attempt_total 15322
telemt_upstream_connect_success_total 15253
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 15310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 5328
telemt_me_reconnect_success_total 5308
telemt_me_reader_eof_total 5623
telemt_me_idle_close_by_peer_total 5623
telemt_me_route_drop_no_conn_total 193871
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 748
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 305
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5627
telemt_me_writer_restored_same_endpoint_total 5303
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 350334
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 4354808464 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 111170909164 (103.54 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 17193.4 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302917
telemt_connections_bad_total 60814
telemt_handshake_timeouts_total 10261
telemt_upstream_connect_attempt_total 9359
telemt_upstream_connect_success_total 9359
telemt_upstream_connect_attempts_per_request{bucket="1"} 9359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3718
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 1927
telemt_me_reconnect_success_total 1913
telemt_me_reader_eof_total 1948
telemt_me_idle_close_by_peer_total 1948
telemt_me_route_drop_no_conn_total 102791
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 279
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1948
telemt_me_writer_restored_same_endpoint_total 1913
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 197778
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 2363104552 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 73716872052 (68.65 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 17877.4 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317459
telemt_connections_bad_total 9798
telemt_handshake_timeouts_total 2713
telemt_upstream_connect_attempt_total 8619
telemt_upstream_connect_success_total 8607
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 1702
telemt_me_reconnect_success_total 1687
telemt_me_reader_eof_total 1782
telemt_me_idle_close_by_peer_total 1781
telemt_me_route_drop_no_conn_total 165104
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 556
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 357
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1786
telemt_me_writer_restored_same_endpoint_total 1686
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 291120
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 14751226396 (13.74 GB)
telemt_user_octets_to_client{user="hello"} 159183154288 (148.25 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 89
```