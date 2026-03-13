# Server Metrics 2026-03-13 22:49:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 147061.5 (40h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4545000
telemt_connections_bad_total 38374
telemt_handshake_timeouts_total 107218
telemt_upstream_connect_attempt_total 30727
telemt_upstream_connect_success_total 30517
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 30727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 6642
telemt_me_reconnect_attempts_total 30969
telemt_me_reconnect_success_total 20845
telemt_me_reader_eof_total 22359
telemt_me_idle_close_by_peer_total 22358
telemt_me_route_drop_no_conn_total 1716329
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4163790
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16583
telemt_desync_full_logged_total 4465
telemt_desync_suppressed_total 12118
telemt_desync_frames_bucket_total{bucket="1_2"} 4130
telemt_desync_frames_bucket_total{bucket="3_10"} 6341
telemt_desync_frames_bucket_total{bucket="gt_10"} 6112
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21462
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20832
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 4165914
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 61132584952 (56.93 GB)
telemt_user_octets_to_client{user="hello"} 1316015269133 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46725.2 (12h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598900
telemt_connections_bad_total 43352
telemt_handshake_timeouts_total 12499
telemt_upstream_connect_attempt_total 13143
telemt_upstream_connect_success_total 12913
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 13143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5223
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 1913
telemt_me_reconnect_attempts_total 11983
telemt_me_reconnect_success_total 8551
telemt_me_reader_eof_total 9058
telemt_me_idle_close_by_peer_total 9057
telemt_me_route_drop_no_conn_total 217865
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517764
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8782
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8543
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 519695
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 5748962689 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 169152690584 (157.54 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 176682.0 (49h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3300279
telemt_connections_bad_total 31815
telemt_handshake_timeouts_total 221038
telemt_upstream_connect_attempt_total 39193
telemt_upstream_connect_success_total 39172
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10302
telemt_me_reconnect_attempts_total 34995
telemt_me_reconnect_success_total 30043
telemt_me_reader_eof_total 31887
telemt_me_idle_close_by_peer_total 31886
telemt_me_route_drop_no_conn_total 1131265
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2740770
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8993
telemt_desync_full_logged_total 3027
telemt_desync_suppressed_total 5966
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3258
telemt_desync_frames_bucket_total{bucket="gt_10"} 4223
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30484
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30002
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2740029
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 44662971612 (41.60 GB)
telemt_user_octets_to_client{user="hello"} 968900455461 (902.36 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 176684.6 (49h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2163050
telemt_connections_bad_total 22841
telemt_handshake_timeouts_total 223106
telemt_upstream_connect_attempt_total 55080
telemt_upstream_connect_success_total 52631
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54806
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20343
telemt_me_reconnect_attempts_total 45814
telemt_me_reconnect_success_total 36796
telemt_me_reader_eof_total 39472
telemt_me_idle_close_by_peer_total 39465
telemt_me_route_drop_no_conn_total 757072
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1760981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 37395
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36772
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 1766863
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 27313705439 (25.44 GB)
telemt_user_octets_to_client{user="hello"} 660138423694 (614.80 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46117.9 (12h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644112
telemt_connections_bad_total 7840
telemt_handshake_timeouts_total 6622
telemt_upstream_connect_attempt_total 10484
telemt_upstream_connect_success_total 10149
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 10484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_keepalive_timeout_total 1431
telemt_me_reconnect_attempts_total 37532
telemt_me_reconnect_success_total 7816
telemt_me_reader_eof_total 8890
telemt_me_idle_close_by_peer_total 8889
telemt_me_route_drop_no_conn_total 244593
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 600498
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1598
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1098
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 8816
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 7811
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 600405
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 9063111124 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 197404829372 (183.85 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 35
```