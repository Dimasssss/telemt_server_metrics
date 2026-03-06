# Server Metrics 2026-03-06 16:21:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 21574.2 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649776
telemt_connections_bad_total 9457
telemt_handshake_timeouts_total 3051
telemt_upstream_connect_attempt_total 10473
telemt_upstream_connect_success_total 10409
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 10436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 2000
telemt_me_reconnect_success_total 1985
telemt_me_reader_eof_total 2085
telemt_me_idle_close_by_peer_total 2085
telemt_me_route_drop_no_conn_total 275425
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3356
telemt_desync_full_logged_total 803
telemt_desync_suppressed_total 2553
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 1150
telemt_desync_frames_bucket_total{bucket="gt_10"} 1407
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2087
telemt_me_writer_restored_same_endpoint_total 1979
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 558845
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 12692726092 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 209040751652 (194.68 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 21574.0 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245075
telemt_connections_bad_total 867
telemt_handshake_timeouts_total 7081
telemt_upstream_connect_attempt_total 10278
telemt_upstream_connect_success_total 10255
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 951
telemt_me_reconnect_success_total 933
telemt_me_reader_eof_total 984
telemt_me_idle_close_by_peer_total 984
telemt_me_route_drop_no_conn_total 139975
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 819
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 985
telemt_me_writer_restored_same_endpoint_total 933
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 225226
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 2599947100 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 90705658840 (84.48 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 21573.7 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488692
telemt_connections_bad_total 5420
telemt_handshake_timeouts_total 50335
telemt_upstream_connect_attempt_total 17641
telemt_upstream_connect_success_total 17562
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 17629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 5856
telemt_me_reconnect_success_total 5832
telemt_me_reader_eof_total 6156
telemt_me_idle_close_by_peer_total 6156
telemt_me_route_drop_no_conn_total 246620
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1037
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 726
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 399
telemt_desync_frames_bucket_total{bucket="gt_10"} 395
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 6168
telemt_me_writer_restored_same_endpoint_total 5825
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 341
telemt_user_connections_total{user="hello"} 417764
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 6113752988 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 130892801652 (121.90 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 20890.1 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429562
telemt_connections_bad_total 133826
telemt_handshake_timeouts_total 11127
telemt_upstream_connect_attempt_total 11465
telemt_upstream_connect_success_total 11464
telemt_upstream_connect_attempts_per_request{bucket="1"} 11464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4636
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 2243
telemt_me_reconnect_success_total 2226
telemt_me_reader_eof_total 2269
telemt_me_idle_close_by_peer_total 2269
telemt_me_route_drop_no_conn_total 135661
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2275
telemt_me_writer_restored_same_endpoint_total 2225
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 248802
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 4432539860 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 89486370672 (83.34 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 21574.2 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387077
telemt_connections_bad_total 11044
telemt_handshake_timeouts_total 3312
telemt_upstream_connect_attempt_total 9677
telemt_upstream_connect_success_total 9665
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 1766
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1845
telemt_me_idle_close_by_peer_total 1844
telemt_me_route_drop_no_conn_total 191238
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 733
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 480
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 355089
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 15271246364 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 182572122988 (170.03 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 92
```