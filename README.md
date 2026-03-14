# Server Metrics 2026-03-14 08:22:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 181427.1 (50h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5136497
telemt_connections_bad_total 42847
telemt_handshake_timeouts_total 116434
telemt_upstream_connect_attempt_total 38188
telemt_upstream_connect_success_total 37939
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 38188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 7417
telemt_me_reconnect_attempts_total 37796
telemt_me_reconnect_success_total 26586
telemt_me_reader_eof_total 28530
telemt_me_idle_close_by_peer_total 28529
telemt_me_route_drop_no_conn_total 1943794
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4710260
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17948
telemt_desync_full_logged_total 4886
telemt_desync_suppressed_total 13062
telemt_desync_frames_bucket_total{bucket="1_2"} 4470
telemt_desync_frames_bucket_total{bucket="3_10"} 6804
telemt_desync_frames_bucket_total{bucket="gt_10"} 6674
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 27321
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26573
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 735
telemt_user_connections_total{user="hello"} 4711698
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 72254746436 (67.29 GB)
telemt_user_octets_to_client{user="hello"} 1507217187413 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81091.1 (22h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890156
telemt_connections_bad_total 53913
telemt_handshake_timeouts_total 16831
telemt_upstream_connect_attempt_total 21816
telemt_upstream_connect_success_total 21537
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 21816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 2176
telemt_me_reconnect_attempts_total 18937
telemt_me_reconnect_success_total 15467
telemt_me_reader_eof_total 16421
telemt_me_idle_close_by_peer_total 16420
telemt_me_route_drop_no_conn_total 295331
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718261
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2155
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 1483
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15800
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 15459
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 720170
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 7582374981 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 250110547000 (232.93 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 211047.6 (58h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3669348
telemt_connections_bad_total 43214
telemt_handshake_timeouts_total 241019
telemt_upstream_connect_attempt_total 47664
telemt_upstream_connect_success_total 47643
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10773
telemt_me_reconnect_attempts_total 41814
telemt_me_reconnect_success_total 36830
telemt_me_reader_eof_total 39113
telemt_me_idle_close_by_peer_total 39112
telemt_me_route_drop_no_conn_total 1257820
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3062716
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10025
telemt_desync_full_logged_total 3376
telemt_desync_suppressed_total 6649
telemt_desync_frames_bucket_total{bucket="1_2"} 1765
telemt_desync_frames_bucket_total{bucket="3_10"} 3628
telemt_desync_frames_bucket_total{bucket="gt_10"} 4632
telemt_pool_swap_total 199
telemt_me_writer_removed_unexpected_total 37342
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36789
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 3061851
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 52035187180 (48.46 GB)
telemt_user_octets_to_client{user="hello"} 1095633578033 (1020.39 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 211050.2 (58h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2437100
telemt_connections_bad_total 23338
telemt_handshake_timeouts_total 296771
telemt_upstream_connect_attempt_total 65611
telemt_upstream_connect_success_total 63114
telemt_upstream_connect_fail_total 2360
telemt_upstream_connect_attempts_per_request{bucket="1"} 65337
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2359
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20574
telemt_me_reconnect_attempts_total 54676
telemt_me_reconnect_success_total 45592
telemt_me_reader_eof_total 48844
telemt_me_idle_close_by_peer_total 48837
telemt_me_route_drop_no_conn_total 817503
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1916797
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3942
telemt_desync_full_logged_total 1287
telemt_desync_suppressed_total 2655
telemt_desync_frames_bucket_total{bucket="1_2"} 1091
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1233
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46268
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45568
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 1922926
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 28792909747 (26.82 GB)
telemt_user_octets_to_client{user="hello"} 699952315986 (651.88 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80483.7 (22h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 871527
telemt_connections_bad_total 10096
telemt_handshake_timeouts_total 10338
telemt_upstream_connect_attempt_total 20373
telemt_upstream_connect_success_total 19826
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 20373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 1627
telemt_me_reconnect_attempts_total 66342
telemt_me_reconnect_success_total 15811
telemt_me_reader_eof_total 17771
telemt_me_idle_close_by_peer_total 17770
telemt_me_route_drop_no_conn_total 333630
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 812439
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2073
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 1420
telemt_desync_frames_bucket_total{bucket="1_2"} 663
telemt_desync_frames_bucket_total{bucket="3_10"} 783
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 17526
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15806
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 812294
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 14874026196 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 273035305248 (254.28 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 100
```