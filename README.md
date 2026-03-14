# Server Metrics 2026-03-14 12:53:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 197700.5 (54h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5749277
telemt_connections_bad_total 65127
telemt_handshake_timeouts_total 126938
telemt_upstream_connect_attempt_total 41450
telemt_upstream_connect_success_total 41184
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 41450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 7869
telemt_me_reconnect_attempts_total 47952
telemt_me_reconnect_success_total 29015
telemt_me_reader_eof_total 31279
telemt_me_idle_close_by_peer_total 31278
telemt_me_route_drop_no_conn_total 2179574
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5271184
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20360
telemt_desync_full_logged_total 5577
telemt_desync_suppressed_total 14783
telemt_desync_frames_bucket_total{bucket="1_2"} 4902
telemt_desync_frames_bucket_total{bucket="3_10"} 7732
telemt_desync_frames_bucket_total{bucket="gt_10"} 7726
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30028
telemt_me_refill_failed_total 586
telemt_me_writer_restored_same_endpoint_total 29002
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1013
telemt_user_connections_total{user="hello"} 5272790
telemt_user_connections_current{user="hello"} 1768
telemt_user_octets_from_client{user="hello"} 82325716184 (76.67 GB)
telemt_user_octets_to_client{user="hello"} 1680514698369 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97364.5 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124812
telemt_connections_bad_total 58966
telemt_handshake_timeouts_total 26748
telemt_upstream_connect_attempt_total 24760
telemt_upstream_connect_success_total 24452
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 24760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10820
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 2437
telemt_me_reconnect_attempts_total 38505
telemt_me_reconnect_success_total 17551
telemt_me_reader_eof_total 19098
telemt_me_idle_close_by_peer_total 19097
telemt_me_route_drop_no_conn_total 381053
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 928730
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2595
telemt_desync_full_logged_total 815
telemt_desync_suppressed_total 1780
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 839
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18454
telemt_me_refill_failed_total 648
telemt_me_writer_restored_same_endpoint_total 17543
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 903
telemt_user_connections_total{user="hello"} 930646
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 10260579429 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 332031806036 (309.23 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 227321.2 (63h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4077226
telemt_connections_bad_total 46645
telemt_handshake_timeouts_total 282948
telemt_upstream_connect_attempt_total 51195
telemt_upstream_connect_success_total 51173
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 51195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11353
telemt_me_reconnect_attempts_total 45533
telemt_me_reconnect_success_total 39524
telemt_me_reader_eof_total 41967
telemt_me_idle_close_by_peer_total 41965
telemt_me_route_drop_no_conn_total 1400960
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3410219
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10893
telemt_desync_full_logged_total 3680
telemt_desync_suppressed_total 7213
telemt_desync_frames_bucket_total{bucket="1_2"} 2001
telemt_desync_frames_bucket_total{bucket="3_10"} 3922
telemt_desync_frames_bucket_total{bucket="gt_10"} 4970
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 40109
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39483
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 3409358
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 58140942392 (54.15 GB)
telemt_user_octets_to_client{user="hello"} 1215331881833 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 227323.5 (63h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2657164
telemt_connections_bad_total 23520
telemt_handshake_timeouts_total 346471
telemt_upstream_connect_attempt_total 69956
telemt_upstream_connect_success_total 67446
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 69682
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21009
telemt_me_reconnect_attempts_total 61886
telemt_me_reconnect_success_total 49101
telemt_me_reader_eof_total 52602
telemt_me_idle_close_by_peer_total 52594
telemt_me_route_drop_no_conn_total 880680
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2074572
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
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 49929
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49076
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 2081120
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 30742574915 (28.63 GB)
telemt_user_octets_to_client{user="hello"} 739113662990 (688.35 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 96757.1 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113146
telemt_connections_bad_total 18174
telemt_handshake_timeouts_total 14242
telemt_upstream_connect_attempt_total 23102
telemt_upstream_connect_success_total 22442
telemt_upstream_connect_fail_total 660
telemt_upstream_connect_attempts_per_request{bucket="1"} 23102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 660
telemt_me_keepalive_timeout_total 1820
telemt_me_reconnect_attempts_total 88158
telemt_me_reconnect_success_total 17616
telemt_me_reader_eof_total 20228
telemt_me_idle_close_by_peer_total 20227
telemt_me_route_drop_no_conn_total 448436
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1031206
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2731
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 1875
telemt_desync_frames_bucket_total{bucket="1_2"} 990
telemt_desync_frames_bucket_total{bucket="3_10"} 958
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19979
telemt_me_refill_failed_total 2199
telemt_me_writer_restored_same_endpoint_total 17611
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2363
telemt_user_connections_total{user="hello"} 1030395
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 17924554600 (16.69 GB)
telemt_user_octets_to_client{user="hello"} 346949286836 (323.12 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 91
```