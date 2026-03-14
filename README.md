# Server Metrics 2026-03-14 12:12:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 195244.9 (54h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5658119
telemt_connections_bad_total 59121
telemt_handshake_timeouts_total 124636
telemt_upstream_connect_attempt_total 40891
telemt_upstream_connect_success_total 40630
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 40891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 7844
telemt_me_reconnect_attempts_total 44971
telemt_me_reconnect_success_total 28598
telemt_me_reader_eof_total 30775
telemt_me_idle_close_by_peer_total 30774
telemt_me_route_drop_no_conn_total 2142977
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5191126
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20021
telemt_desync_full_logged_total 5479
telemt_desync_suppressed_total 14542
telemt_desync_frames_bucket_total{bucket="1_2"} 4841
telemt_desync_frames_bucket_total{bucket="3_10"} 7623
telemt_desync_frames_bucket_total{bucket="gt_10"} 7557
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29524
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28585
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 926
telemt_user_connections_total{user="hello"} 5192682
telemt_user_connections_current{user="hello"} 1744
telemt_user_octets_from_client{user="hello"} 80543386840 (75.01 GB)
telemt_user_octets_to_client{user="hello"} 1652150474565 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94908.8 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091932
telemt_connections_bad_total 58940
telemt_handshake_timeouts_total 25351
telemt_upstream_connect_attempt_total 24514
telemt_upstream_connect_success_total 24210
telemt_upstream_connect_fail_total 304
telemt_upstream_connect_attempts_per_request{bucket="1"} 24514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 304
telemt_me_keepalive_timeout_total 2406
telemt_me_reconnect_attempts_total 35166
telemt_me_reconnect_success_total 17444
telemt_me_reader_eof_total 18888
telemt_me_idle_close_by_peer_total 18887
telemt_me_route_drop_no_conn_total 369161
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 899791
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2480
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1699
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 1026
telemt_desync_frames_bucket_total{bucket="gt_10"} 815
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18244
telemt_me_refill_failed_total 547
telemt_me_writer_restored_same_endpoint_total 17436
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 800
telemt_user_connections_total{user="hello"} 901702
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 9843284345 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 319033602244 (297.12 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 224865.3 (62h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4014762
telemt_connections_bad_total 46491
telemt_handshake_timeouts_total 274220
telemt_upstream_connect_attempt_total 50618
telemt_upstream_connect_success_total 50597
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11269
telemt_me_reconnect_attempts_total 45092
telemt_me_reconnect_success_total 39091
telemt_me_reader_eof_total 41522
telemt_me_idle_close_by_peer_total 41520
telemt_me_route_drop_no_conn_total 1379712
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3358164
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10789
telemt_desync_full_logged_total 3643
telemt_desync_suppressed_total 7146
telemt_desync_frames_bucket_total{bucket="1_2"} 1969
telemt_desync_frames_bucket_total{bucket="3_10"} 3899
telemt_desync_frames_bucket_total{bucket="gt_10"} 4921
telemt_pool_swap_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39668
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39050
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 3357315
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 57422276784 (53.48 GB)
telemt_user_octets_to_client{user="hello"} 1198669970949 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 224867.9 (62h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2623666
telemt_connections_bad_total 23512
telemt_handshake_timeouts_total 338182
telemt_upstream_connect_attempt_total 69372
telemt_upstream_connect_success_total 66864
telemt_upstream_connect_fail_total 2371
telemt_upstream_connect_attempts_per_request{bucket="1"} 69098
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2370
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20961
telemt_me_reconnect_attempts_total 61434
telemt_me_reconnect_success_total 48651
telemt_me_reader_eof_total 52117
telemt_me_idle_close_by_peer_total 52109
telemt_me_route_drop_no_conn_total 871557
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2051170
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 49475
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48626
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 824
telemt_user_connections_total{user="hello"} 2057596
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 30450459135 (28.36 GB)
telemt_user_octets_to_client{user="hello"} 732792856106 (682.47 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94301.2 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077506
telemt_connections_bad_total 18118
telemt_handshake_timeouts_total 13881
telemt_upstream_connect_attempt_total 22859
telemt_upstream_connect_success_total 22220
telemt_upstream_connect_fail_total 639
telemt_upstream_connect_attempts_per_request{bucket="1"} 22859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 639
telemt_me_keepalive_timeout_total 1792
telemt_me_reconnect_attempts_total 83940
telemt_me_reconnect_success_total 17526
telemt_me_reader_eof_total 20009
telemt_me_idle_close_by_peer_total 20008
telemt_me_route_drop_no_conn_total 435704
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998133
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2668
telemt_desync_full_logged_total 836
telemt_desync_suppressed_total 1832
telemt_desync_frames_bucket_total{bucket="1_2"} 962
telemt_desync_frames_bucket_total{bucket="3_10"} 944
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19760
telemt_me_refill_failed_total 2070
telemt_me_writer_restored_same_endpoint_total 17521
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2234
telemt_user_connections_total{user="hello"} 997333
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 17241258000 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 336143291180 (313.06 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 107
```