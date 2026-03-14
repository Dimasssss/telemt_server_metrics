# Server Metrics 2026-03-14 11:26:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 192482.8 (53h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5555386
telemt_connections_bad_total 56776
telemt_handshake_timeouts_total 122684
telemt_upstream_connect_attempt_total 40361
telemt_upstream_connect_success_total 40104
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 40361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 7708
telemt_me_reconnect_attempts_total 44575
telemt_me_reconnect_success_total 28204
telemt_me_reader_eof_total 30366
telemt_me_idle_close_by_peer_total 30365
telemt_me_route_drop_no_conn_total 2101632
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5095276
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19481
telemt_desync_full_logged_total 5329
telemt_desync_suppressed_total 14152
telemt_desync_frames_bucket_total{bucket="1_2"} 4740
telemt_desync_frames_bucket_total{bucket="3_10"} 7430
telemt_desync_frames_bucket_total{bucket="gt_10"} 7311
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 29126
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28191
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 922
telemt_user_connections_total{user="hello"} 5096716
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 78780196844 (73.37 GB)
telemt_user_octets_to_client{user="hello"} 1622296165177 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92146.4 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051640
telemt_connections_bad_total 58720
telemt_handshake_timeouts_total 23753
telemt_upstream_connect_attempt_total 24136
telemt_upstream_connect_success_total 23840
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 24136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 2299
telemt_me_reconnect_attempts_total 30868
telemt_me_reconnect_success_total 17211
telemt_me_reader_eof_total 18528
telemt_me_idle_close_by_peer_total 18527
telemt_me_route_drop_no_conn_total 354285
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 862828
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2423
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1665
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17883
telemt_me_refill_failed_total 420
telemt_me_writer_restored_same_endpoint_total 17203
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 672
telemt_user_connections_total{user="hello"} 864742
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 9442929501 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 302507422876 (281.73 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 222103.4 (61h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3940080
telemt_connections_bad_total 46183
telemt_handshake_timeouts_total 263964
telemt_upstream_connect_attempt_total 50127
telemt_upstream_connect_success_total 50106
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11089
telemt_me_reconnect_attempts_total 44731
telemt_me_reconnect_success_total 38732
telemt_me_reader_eof_total 41133
telemt_me_idle_close_by_peer_total 41131
telemt_me_route_drop_no_conn_total 1354245
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3295264
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10617
telemt_desync_full_logged_total 3590
telemt_desync_suppressed_total 7027
telemt_desync_frames_bucket_total{bucket="1_2"} 1930
telemt_desync_frames_bucket_total{bucket="3_10"} 3842
telemt_desync_frames_bucket_total{bucket="gt_10"} 4845
telemt_pool_swap_total 205
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 39306
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38691
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 3294412
telemt_user_connections_current{user="hello"} 1031
telemt_user_octets_from_client{user="hello"} 56134706644 (52.28 GB)
telemt_user_octets_to_client{user="hello"} 1180256024645 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 222105.9 (61h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2584546
telemt_connections_bad_total 23476
telemt_handshake_timeouts_total 329010
telemt_upstream_connect_attempt_total 68725
telemt_upstream_connect_success_total 66219
telemt_upstream_connect_fail_total 2369
telemt_upstream_connect_attempts_per_request{bucket="1"} 68451
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2368
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20806
telemt_me_reconnect_attempts_total 60920
telemt_me_reconnect_success_total 48142
telemt_me_reader_eof_total 51585
telemt_me_idle_close_by_peer_total 51577
telemt_me_route_drop_no_conn_total 861124
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2023189
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4085
telemt_desync_full_logged_total 1341
telemt_desync_suppressed_total 2744
telemt_desync_frames_bucket_total{bucket="1_2"} 1160
telemt_desync_frames_bucket_total{bucket="3_10"} 1666
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 190
telemt_me_writer_removed_unexpected_total 48959
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48117
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 817
telemt_user_connections_total{user="hello"} 2029528
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 30125891279 (28.06 GB)
telemt_user_octets_to_client{user="hello"} 727045038186 (677.11 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91539.2 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037321
telemt_connections_bad_total 18075
telemt_handshake_timeouts_total 13631
telemt_upstream_connect_attempt_total 22550
telemt_upstream_connect_success_total 21940
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 22550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 1741
telemt_me_reconnect_attempts_total 79695
telemt_me_reconnect_success_total 17378
telemt_me_reader_eof_total 19734
telemt_me_idle_close_by_peer_total 19733
telemt_me_route_drop_no_conn_total 419934
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959698
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2589
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1780
telemt_desync_frames_bucket_total{bucket="1_2"} 906
telemt_desync_frames_bucket_total{bucket="3_10"} 934
telemt_desync_frames_bucket_total{bucket="gt_10"} 749
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19483
telemt_me_refill_failed_total 1942
telemt_me_writer_restored_same_endpoint_total 17373
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2105
telemt_user_connections_total{user="hello"} 958912
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 16862445660 (15.70 GB)
telemt_user_octets_to_client{user="hello"} 324112912640 (301.85 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 104
```