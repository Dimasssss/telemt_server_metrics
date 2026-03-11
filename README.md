# Server Metrics 2026-03-11 15:17:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 89397.6 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2188227
telemt_connections_bad_total 35890
telemt_handshake_timeouts_total 52462
telemt_upstream_connect_attempt_total 18803
telemt_upstream_connect_success_total 18791
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4890
telemt_me_reconnect_attempts_total 32119
telemt_me_reconnect_success_total 14253
telemt_me_reader_eof_total 15475
telemt_me_idle_close_by_peer_total 15475
telemt_me_route_drop_no_conn_total 810492
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2002778
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10477
telemt_desync_full_logged_total 2846
telemt_desync_suppressed_total 7631
telemt_desync_frames_bucket_total{bucket="1_2"} 2605
telemt_desync_frames_bucket_total{bucket="3_10"} 4031
telemt_desync_frames_bucket_total{bucket="gt_10"} 3841
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14968
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14247
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 715
telemt_user_connections_total{user="hello"} 2001244
telemt_user_connections_current{user="hello"} 1325
telemt_user_octets_from_client{user="hello"} 26860866492 (25.02 GB)
telemt_user_octets_to_client{user="hello"} 568810952424 (529.75 GB)
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89454.3 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 813684
telemt_connections_bad_total 13251
telemt_handshake_timeouts_total 55128
telemt_upstream_connect_attempt_total 28358
telemt_upstream_connect_success_total 25402
telemt_upstream_connect_fail_total 2956
telemt_upstream_connect_attempts_per_request{bucket="1"} 28358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2956
telemt_me_keepalive_timeout_total 2550
telemt_me_reconnect_attempts_total 20042
telemt_me_reconnect_success_total 17949
telemt_me_reader_eof_total 19008
telemt_me_idle_close_by_peer_total 19005
telemt_me_route_drop_no_conn_total 318782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691301
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2883
telemt_desync_full_logged_total 915
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 952
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18211
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17926
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 693777
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 7985927742 (7.44 GB)
telemt_user_octets_to_client{user="hello"} 195530238468 (182.10 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 89454.3 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1413641
telemt_connections_bad_total 8647
telemt_handshake_timeouts_total 123838
telemt_upstream_connect_attempt_total 23669
telemt_upstream_connect_success_total 23386
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 23669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 36143
telemt_me_reconnect_success_total 17788
telemt_me_reader_eof_total 19165
telemt_me_idle_close_by_peer_total 19165
telemt_me_route_drop_no_conn_total 513696
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1229311
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3257
telemt_desync_full_logged_total 964
telemt_desync_suppressed_total 2293
telemt_desync_frames_bucket_total{bucket="1_2"} 800
telemt_desync_frames_bucket_total{bucket="3_10"} 1234
telemt_desync_frames_bucket_total{bucket="gt_10"} 1223
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18605
telemt_me_refill_failed_total 569
telemt_me_writer_restored_same_endpoint_total 17777
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 817
telemt_user_connections_total{user="hello"} 1229064
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 14803369429 (13.79 GB)
telemt_user_octets_to_client{user="hello"} 368195709273 (342.91 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 89454.7 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012454
telemt_connections_bad_total 77854
telemt_handshake_timeouts_total 97463
telemt_upstream_connect_attempt_total 23971
telemt_upstream_connect_success_total 23971
telemt_upstream_connect_attempts_per_request{bucket="1"} 23971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1007
telemt_me_reconnect_attempts_total 20570
telemt_me_reconnect_success_total 19495
telemt_me_reader_eof_total 20682
telemt_me_idle_close_by_peer_total 20681
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 331124
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 809497
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1711
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 608
telemt_desync_frames_bucket_total{bucket="3_10"} 609
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19734
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19466
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 808820
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 9530933664 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 238341967992 (221.97 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89454.5 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1118635
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 11307
telemt_upstream_connect_attempt_total 24253
telemt_upstream_connect_success_total 24147
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 24253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1948
telemt_me_reconnect_attempts_total 23619
telemt_me_reconnect_success_total 19532
telemt_me_reader_eof_total 20601
telemt_me_idle_close_by_peer_total 20601
telemt_me_route_drop_no_conn_total 398567
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016849
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3923
telemt_desync_full_logged_total 1430
telemt_desync_suppressed_total 2493
telemt_desync_frames_bucket_total{bucket="1_2"} 1346
telemt_desync_frames_bucket_total{bucket="3_10"} 1471
telemt_desync_frames_bucket_total{bucket="gt_10"} 1106
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19912
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19532
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 1016563
telemt_user_connections_current{user="hello"} 669
telemt_user_octets_from_client{user="hello"} 14452503843 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 356400215150 (331.92 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 97
```