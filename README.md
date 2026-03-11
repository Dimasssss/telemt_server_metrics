# Server Metrics 2026-03-11 07:37:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 61846.7 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1247513
telemt_connections_bad_total 13655
telemt_handshake_timeouts_total 39265
telemt_upstream_connect_attempt_total 12887
telemt_upstream_connect_success_total 12878
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 716
telemt_me_reconnect_attempts_total 21438
telemt_me_reconnect_success_total 9754
telemt_me_reader_eof_total 10597
telemt_me_idle_close_by_peer_total 10597
telemt_me_route_drop_no_conn_total 459628
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1127127
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5501
telemt_desync_full_logged_total 1540
telemt_desync_suppressed_total 3961
telemt_desync_frames_bucket_total{bucket="1_2"} 1454
telemt_desync_frames_bucket_total{bucket="3_10"} 2077
telemt_desync_frames_bucket_total{bucket="gt_10"} 1970
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10216
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9748
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 1126788
telemt_user_connections_current{user="hello"} 1142
telemt_user_octets_from_client{user="hello"} 14912324832 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 331538584868 (308.77 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61903.3 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483001
telemt_connections_bad_total 7289
telemt_handshake_timeouts_total 24322
telemt_upstream_connect_attempt_total 21762
telemt_upstream_connect_success_total 18845
telemt_upstream_connect_fail_total 2917
telemt_upstream_connect_attempts_per_request{bucket="1"} 21762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2917
telemt_me_keepalive_timeout_total 2044
telemt_me_reconnect_attempts_total 13632
telemt_me_reconnect_success_total 12806
telemt_me_reader_eof_total 13545
telemt_me_idle_close_by_peer_total 13543
telemt_me_route_drop_no_conn_total 211395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411697
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2063
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1428
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12952
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12784
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 413965
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 4042504210 (3.76 GB)
telemt_user_octets_to_client{user="hello"} 108898923452 (101.42 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 61903.2 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814353
telemt_connections_bad_total 6905
telemt_handshake_timeouts_total 44088
telemt_upstream_connect_attempt_total 16729
telemt_upstream_connect_success_total 16523
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 736
telemt_me_reconnect_attempts_total 24710
telemt_me_reconnect_success_total 12355
telemt_me_reader_eof_total 13316
telemt_me_idle_close_by_peer_total 13316
telemt_me_route_drop_no_conn_total 276505
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728534
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 619
telemt_desync_suppressed_total 1487
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 767
telemt_desync_frames_bucket_total{bucket="gt_10"} 848
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 12897
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12344
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 729330
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 8558775181 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 215252393105 (200.47 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 61903.7 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622408
telemt_connections_bad_total 57976
telemt_handshake_timeouts_total 61471
telemt_upstream_connect_attempt_total 17380
telemt_upstream_connect_success_total 17380
telemt_upstream_connect_attempts_per_request{bucket="1"} 17380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 662
telemt_me_reconnect_attempts_total 15340
telemt_me_reconnect_success_total 14290
telemt_me_reader_eof_total 15176
telemt_me_idle_close_by_peer_total 15175
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 190870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482366
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1101
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 670
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 14457
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14268
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 481780
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 5709062712 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 131745724516 (122.70 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61903.2 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650166
telemt_connections_bad_total 5970
telemt_handshake_timeouts_total 4688
telemt_upstream_connect_attempt_total 17232
telemt_upstream_connect_success_total 17162
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 690
telemt_me_reconnect_attempts_total 17745
telemt_me_reconnect_success_total 13959
telemt_me_reader_eof_total 14749
telemt_me_idle_close_by_peer_total 14749
telemt_me_route_drop_no_conn_total 217091
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592582
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2744
telemt_desync_full_logged_total 1036
telemt_desync_suppressed_total 1708
telemt_desync_frames_bucket_total{bucket="1_2"} 967
telemt_desync_frames_bucket_total{bucket="3_10"} 1146
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 14254
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13959
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 592293
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 10042138723 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 216944401050 (202.05 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 77
```