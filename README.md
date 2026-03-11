# Server Metrics 2026-03-11 09:09:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 67344.4 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1420452
telemt_connections_bad_total 16781
telemt_handshake_timeouts_total 40414
telemt_upstream_connect_attempt_total 14045
telemt_upstream_connect_success_total 14036
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 776
telemt_me_reconnect_attempts_total 22331
telemt_me_reconnect_success_total 10644
telemt_me_reader_eof_total 11533
telemt_me_idle_close_by_peer_total 11533
telemt_me_route_drop_no_conn_total 521893
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1288547
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6320
telemt_desync_full_logged_total 1746
telemt_desync_suppressed_total 4574
telemt_desync_frames_bucket_total{bucket="1_2"} 1667
telemt_desync_frames_bucket_total{bucket="3_10"} 2398
telemt_desync_frames_bucket_total{bucket="gt_10"} 2255
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11111
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10638
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 1288215
telemt_user_connections_current{user="hello"} 1415
telemt_user_octets_from_client{user="hello"} 17030481828 (15.86 GB)
telemt_user_octets_to_client{user="hello"} 369783498492 (344.39 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67401.1 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547655
telemt_connections_bad_total 9238
telemt_handshake_timeouts_total 30503
telemt_upstream_connect_attempt_total 22964
telemt_upstream_connect_success_total 20038
telemt_upstream_connect_fail_total 2926
telemt_upstream_connect_attempts_per_request{bucket="1"} 22964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2926
telemt_me_keepalive_timeout_total 2078
telemt_me_reconnect_attempts_total 14565
telemt_me_reconnect_success_total 13729
telemt_me_reader_eof_total 14532
telemt_me_idle_close_by_peer_total 14530
telemt_me_route_drop_no_conn_total 229757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464080
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2153
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1491
telemt_desync_frames_bucket_total{bucket="1_2"} 718
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 659
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13892
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13707
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 466318
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 4557271562 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 124903513272 (116.33 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 67400.9 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 950042
telemt_connections_bad_total 7442
telemt_handshake_timeouts_total 88300
telemt_upstream_connect_attempt_total 18174
telemt_upstream_connect_success_total 17954
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 18174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 761
telemt_me_reconnect_attempts_total 25880
telemt_me_reconnect_success_total 13518
telemt_me_reader_eof_total 14530
telemt_me_idle_close_by_peer_total 14530
telemt_me_route_drop_no_conn_total 312579
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816332
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2351
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1655
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 926
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14075
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13507
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 557
telemt_user_connections_total{user="hello"} 817168
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 9695177413 (9.03 GB)
telemt_user_octets_to_client{user="hello"} 247293874081 (230.31 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 67401.4 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697086
telemt_connections_bad_total 63192
telemt_handshake_timeouts_total 68056
telemt_upstream_connect_attempt_total 18614
telemt_upstream_connect_success_total 18614
telemt_upstream_connect_attempts_per_request{bucket="1"} 18614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 16313
telemt_me_reconnect_success_total 15259
telemt_me_reader_eof_total 16198
telemt_me_idle_close_by_peer_total 16197
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 217762
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544253
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1244
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15439
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15236
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 543627
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 6370718208 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 153598141728 (143.05 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 67401.0 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738582
telemt_connections_bad_total 5983
telemt_handshake_timeouts_total 6972
telemt_upstream_connect_attempt_total 18367
telemt_upstream_connect_success_total 18293
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 18612
telemt_me_reconnect_success_total 14820
telemt_me_reader_eof_total 15667
telemt_me_idle_close_by_peer_total 15667
telemt_me_route_drop_no_conn_total 251249
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668873
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2888
telemt_desync_full_logged_total 1094
telemt_desync_suppressed_total 1794
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 683
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 15126
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14820
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 668561
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 10696793851 (9.96 GB)
telemt_user_octets_to_client{user="hello"} 240620047942 (224.09 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 98
```