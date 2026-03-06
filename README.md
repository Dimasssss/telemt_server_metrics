# Server Metrics 2026-03-06 17:28:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 25581.4 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760331
telemt_connections_bad_total 13096
telemt_handshake_timeouts_total 3284
telemt_upstream_connect_attempt_total 13125
telemt_upstream_connect_success_total 13045
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 13078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 2662
telemt_me_reconnect_success_total 2643
telemt_me_reader_eof_total 2769
telemt_me_idle_close_by_peer_total 2769
telemt_me_route_drop_no_conn_total 321093
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3870
telemt_desync_full_logged_total 948
telemt_desync_suppressed_total 2922
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 1358
telemt_desync_frames_bucket_total{bucket="gt_10"} 1603
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2772
telemt_me_writer_restored_same_endpoint_total 2637
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 653153
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 13736279156 (12.79 GB)
telemt_user_octets_to_client{user="hello"} 242348565764 (225.70 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 25581.1 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282674
telemt_connections_bad_total 1124
telemt_handshake_timeouts_total 8284
telemt_upstream_connect_attempt_total 11481
telemt_upstream_connect_success_total 11448
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 976
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 1005
telemt_me_idle_close_by_peer_total 1005
telemt_me_route_drop_no_conn_total 153756
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 900
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 407
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_restored_same_endpoint_total 952
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 260170
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 3178086820 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 104718397256 (97.53 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 25581.1 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553344
telemt_connections_bad_total 5542
telemt_handshake_timeouts_total 52613
telemt_upstream_connect_attempt_total 22754
telemt_upstream_connect_success_total 22645
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 22724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 340
telemt_me_reconnect_attempts_total 7964
telemt_me_reconnect_success_total 7934
telemt_me_reader_eof_total 8430
telemt_me_idle_close_by_peer_total 8430
telemt_me_route_drop_no_conn_total 292485
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1389
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 986
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 554
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8445
telemt_me_writer_restored_same_endpoint_total 7927
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 476675
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 7152502440 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 147561772680 (137.43 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 24897.3 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531325
telemt_connections_bad_total 178963
telemt_handshake_timeouts_total 13640
telemt_upstream_connect_attempt_total 17155
telemt_upstream_connect_success_total 17153
telemt_upstream_connect_attempts_per_request{bucket="1"} 17153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7468
telemt_me_keepalive_timeout_total 240
telemt_me_reconnect_attempts_total 4813
telemt_me_reconnect_success_total 4789
telemt_me_reader_eof_total 5019
telemt_me_idle_close_by_peer_total 5019
telemt_me_route_drop_no_conn_total 173414
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 366
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 5026
telemt_me_writer_restored_same_endpoint_total 4788
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 301292
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 5021460572 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 105490795664 (98.25 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 25581.7 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472583
telemt_connections_bad_total 11135
telemt_handshake_timeouts_total 4779
telemt_upstream_connect_attempt_total 10860
telemt_upstream_connect_success_total 10843
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1867
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 223088
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 895
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1871
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 433569
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 20607710880 (19.19 GB)
telemt_user_octets_to_client{user="hello"} 209102023724 (194.74 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 85
```