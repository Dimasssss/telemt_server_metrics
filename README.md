# Server Metrics 2026-03-11 05:20:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53611.5 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041909
telemt_connections_bad_total 11416
telemt_handshake_timeouts_total 35405
telemt_upstream_connect_attempt_total 11464
telemt_upstream_connect_success_total 11455
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 543
telemt_me_reconnect_attempts_total 20404
telemt_me_reconnect_success_total 8726
telemt_me_reader_eof_total 9502
telemt_me_idle_close_by_peer_total 9502
telemt_me_route_drop_no_conn_total 386200
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935940
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4274
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 3062
telemt_desync_frames_bucket_total{bucket="1_2"} 1197
telemt_desync_frames_bucket_total{bucket="3_10"} 1606
telemt_desync_frames_bucket_total{bucket="gt_10"} 1471
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9171
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8720
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 935645
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 12520537260 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 273165318236 (254.41 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53668.3 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405026
telemt_connections_bad_total 2790
telemt_handshake_timeouts_total 19399
telemt_upstream_connect_attempt_total 19967
telemt_upstream_connect_success_total 17062
telemt_upstream_connect_fail_total 2905
telemt_upstream_connect_attempts_per_request{bucket="1"} 19967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2905
telemt_me_keepalive_timeout_total 1788
telemt_me_reconnect_attempts_total 12239
telemt_me_reconnect_success_total 11419
telemt_me_reader_eof_total 12064
telemt_me_idle_close_by_peer_total 12062
telemt_me_route_drop_no_conn_total 190931
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348363
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1860
telemt_desync_full_logged_total 556
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 11551
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11398
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 350633
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 3358353850 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 85621915020 (79.74 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 53668.1 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691390
telemt_connections_bad_total 5922
telemt_handshake_timeouts_total 37809
telemt_upstream_connect_attempt_total 14511
telemt_upstream_connect_success_total 14319
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 14511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 21621
telemt_me_reconnect_success_total 10549
telemt_me_reader_eof_total 11396
telemt_me_idle_close_by_peer_total 11396
telemt_me_route_drop_no_conn_total 232914
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617047
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1717
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1210
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 729
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11035
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10538
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 617907
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 7546456253 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 184079853357 (171.44 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 53668.5 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526762
telemt_connections_bad_total 50448
telemt_handshake_timeouts_total 54980
telemt_upstream_connect_attempt_total 15416
telemt_upstream_connect_success_total 15416
telemt_upstream_connect_attempts_per_request{bucket="1"} 15416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6757
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 493
telemt_me_reconnect_attempts_total 13765
telemt_me_reconnect_success_total 12722
telemt_me_reader_eof_total 13507
telemt_me_idle_close_by_peer_total 13507
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 155689
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406901
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 871
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 514
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12869
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12701
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 406539
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 4978579268 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 111734146456 (104.06 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53668.2 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550378
telemt_connections_bad_total 5831
telemt_handshake_timeouts_total 3666
telemt_upstream_connect_attempt_total 15377
telemt_upstream_connect_success_total 15313
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 563
telemt_me_reconnect_attempts_total 16360
telemt_me_reconnect_success_total 12578
telemt_me_reader_eof_total 13278
telemt_me_idle_close_by_peer_total 13278
telemt_me_route_drop_no_conn_total 179002
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502346
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2455
telemt_desync_full_logged_total 960
telemt_desync_suppressed_total 1495
telemt_desync_frames_bucket_total{bucket="1_2"} 899
telemt_desync_frames_bucket_total{bucket="3_10"} 1044
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 12855
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12578
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 501969
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 9044140868 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 177008459092 (164.85 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 68
```