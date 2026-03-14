# Server Metrics 2026-03-14 08:27:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 181733.8 (50h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5146223
telemt_connections_bad_total 43085
telemt_handshake_timeouts_total 116560
telemt_upstream_connect_attempt_total 38228
telemt_upstream_connect_success_total 37979
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 38228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 7418
telemt_me_reconnect_attempts_total 37836
telemt_me_reconnect_success_total 26626
telemt_me_reader_eof_total 28572
telemt_me_idle_close_by_peer_total 28571
telemt_me_route_drop_no_conn_total 1947816
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4719425
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17992
telemt_desync_full_logged_total 4901
telemt_desync_suppressed_total 13091
telemt_desync_frames_bucket_total{bucket="1_2"} 4484
telemt_desync_frames_bucket_total{bucket="3_10"} 6821
telemt_desync_frames_bucket_total{bucket="gt_10"} 6687
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 27363
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26613
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 4720872
telemt_user_connections_current{user="hello"} 1617
telemt_user_octets_from_client{user="hello"} 72392584268 (67.42 GB)
telemt_user_octets_to_client{user="hello"} 1509977501073 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81397.7 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 894616
telemt_connections_bad_total 53914
telemt_handshake_timeouts_total 17066
telemt_upstream_connect_attempt_total 21899
telemt_upstream_connect_success_total 21619
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 21899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 2177
telemt_me_reconnect_attempts_total 20028
telemt_me_reconnect_success_total 15534
telemt_me_reader_eof_total 16521
telemt_me_idle_close_by_peer_total 16520
telemt_me_route_drop_no_conn_total 296982
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722393
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2161
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1486
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15900
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 15526
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 724292
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 7657701605 (7.13 GB)
telemt_user_octets_to_client{user="hello"} 251002841140 (233.76 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 211354.4 (58h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3675740
telemt_connections_bad_total 43220
telemt_handshake_timeouts_total 241488
telemt_upstream_connect_attempt_total 47688
telemt_upstream_connect_success_total 47667
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10775
telemt_me_reconnect_attempts_total 41838
telemt_me_reconnect_success_total 36854
telemt_me_reader_eof_total 39137
telemt_me_idle_close_by_peer_total 39136
telemt_me_route_drop_no_conn_total 1260348
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3068438
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10040
telemt_desync_full_logged_total 3382
telemt_desync_suppressed_total 6658
telemt_desync_frames_bucket_total{bucket="1_2"} 1770
telemt_desync_frames_bucket_total{bucket="3_10"} 3632
telemt_desync_frames_bucket_total{bucket="gt_10"} 4638
telemt_pool_swap_total 199
telemt_me_writer_removed_unexpected_total 37366
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36813
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 3067569
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 52154131920 (48.57 GB)
telemt_user_octets_to_client{user="hello"} 1096906089077 (1021.57 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 211356.9 (58h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2440942
telemt_connections_bad_total 23342
telemt_handshake_timeouts_total 297555
telemt_upstream_connect_attempt_total 65673
telemt_upstream_connect_success_total 63176
telemt_upstream_connect_fail_total 2360
telemt_upstream_connect_attempts_per_request{bucket="1"} 65399
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2359
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20575
telemt_me_reconnect_attempts_total 54738
telemt_me_reconnect_success_total 45654
telemt_me_reader_eof_total 48906
telemt_me_idle_close_by_peer_total 48899
telemt_me_route_drop_no_conn_total 818533
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1919585
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3948
telemt_desync_full_logged_total 1288
telemt_desync_suppressed_total 2660
telemt_desync_frames_bucket_total{bucket="1_2"} 1094
telemt_desync_frames_bucket_total{bucket="3_10"} 1620
telemt_desync_frames_bucket_total{bucket="gt_10"} 1234
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46330
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45630
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 1925716
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 28838216735 (26.86 GB)
telemt_user_octets_to_client{user="hello"} 700814148406 (652.68 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 80790.5 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 876444
telemt_connections_bad_total 10436
telemt_handshake_timeouts_total 10399
telemt_upstream_connect_attempt_total 20408
telemt_upstream_connect_success_total 19861
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 20408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 1627
telemt_me_reconnect_attempts_total 66377
telemt_me_reconnect_success_total 15845
telemt_me_reader_eof_total 17807
telemt_me_idle_close_by_peer_total 17806
telemt_me_route_drop_no_conn_total 335158
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816768
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2084
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 17562
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15840
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1717
telemt_user_connections_total{user="hello"} 816623
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 14930332800 (13.90 GB)
telemt_user_octets_to_client{user="hello"} 275676929824 (256.74 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 103
```