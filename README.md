# Server Metrics 2026-03-11 03:18:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 46294.6 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891231
telemt_connections_bad_total 10070
telemt_handshake_timeouts_total 20592
telemt_upstream_connect_attempt_total 10033
telemt_upstream_connect_success_total 10024
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 517
telemt_me_reconnect_attempts_total 19318
telemt_me_reconnect_success_total 7647
telemt_me_reader_eof_total 8348
telemt_me_idle_close_by_peer_total 8348
telemt_me_route_drop_no_conn_total 350490
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 826941
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3833
telemt_desync_full_logged_total 1064
telemt_desync_suppressed_total 2769
telemt_desync_frames_bucket_total{bucket="1_2"} 1098
telemt_desync_frames_bucket_total{bucket="3_10"} 1440
telemt_desync_frames_bucket_total{bucket="gt_10"} 1295
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8079
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7641
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 826672
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 11093220172 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 246633219052 (229.70 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 46351.4 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369038
telemt_connections_bad_total 2486
telemt_handshake_timeouts_total 18402
telemt_upstream_connect_attempt_total 18004
telemt_upstream_connect_success_total 15112
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1760
telemt_me_reconnect_attempts_total 10637
telemt_me_reconnect_success_total 9820
telemt_me_reader_eof_total 10368
telemt_me_idle_close_by_peer_total 10366
telemt_me_route_drop_no_conn_total 179776
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316717
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1800
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1278
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 643
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 9937
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9799
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 318987
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 3029315562 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 74991171628 (69.84 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 46351.2 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618675
telemt_connections_bad_total 5341
telemt_handshake_timeouts_total 34781
telemt_upstream_connect_attempt_total 12576
telemt_upstream_connect_success_total 12412
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 12576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 548
telemt_me_reconnect_attempts_total 20061
telemt_me_reconnect_success_total 8992
telemt_me_reader_eof_total 9760
telemt_me_idle_close_by_peer_total 9760
telemt_me_route_drop_no_conn_total 210103
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549536
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1605
telemt_desync_full_logged_total 473
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 694
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 9458
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8981
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 550430
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 7092836657 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 167738601429 (156.22 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 46351.5 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465757
telemt_connections_bad_total 43764
telemt_handshake_timeouts_total 45469
telemt_upstream_connect_attempt_total 13505
telemt_upstream_connect_success_total 13505
telemt_upstream_connect_attempts_per_request{bucket="1"} 13505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 466
telemt_me_reconnect_attempts_total 12201
telemt_me_reconnect_success_total 11163
telemt_me_reader_eof_total 11847
telemt_me_idle_close_by_peer_total 11847
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 139019
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362802
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 781
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 11295
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11144
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 362471
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 4418100688 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 96690189688 (90.05 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 46351.3 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491719
telemt_connections_bad_total 5810
telemt_handshake_timeouts_total 3063
telemt_upstream_connect_attempt_total 13610
telemt_upstream_connect_success_total 13552
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 538
telemt_me_reconnect_attempts_total 14945
telemt_me_reconnect_success_total 11167
telemt_me_reader_eof_total 11783
telemt_me_idle_close_by_peer_total 11783
telemt_me_route_drop_no_conn_total 157949
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447819
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2334
telemt_desync_full_logged_total 910
telemt_desync_suppressed_total 1424
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 11427
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11167
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 447473
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 8594367008 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 161507300732 (150.42 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 41
```