# Server Metrics 2026-03-13 23:05:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 147981.7 (41h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4555467
telemt_connections_bad_total 38380
telemt_handshake_timeouts_total 107570
telemt_upstream_connect_attempt_total 30990
telemt_upstream_connect_success_total 30776
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 30989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 6645
telemt_me_reconnect_attempts_total 31186
telemt_me_reconnect_success_total 21058
telemt_me_reader_eof_total 22592
telemt_me_idle_close_by_peer_total 22591
telemt_me_route_drop_no_conn_total 1722131
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4173693
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16585
telemt_desync_full_logged_total 4466
telemt_desync_suppressed_total 12119
telemt_desync_frames_bucket_total{bucket="1_2"} 4130
telemt_desync_frames_bucket_total{bucket="3_10"} 6341
telemt_desync_frames_bucket_total{bucket="gt_10"} 6114
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 21680
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21045
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 4175625
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 61274303788 (57.07 GB)
telemt_user_octets_to_client{user="hello"} 1319813232333 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47645.3 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603729
telemt_connections_bad_total 44070
telemt_handshake_timeouts_total 12531
telemt_upstream_connect_attempt_total 13482
telemt_upstream_connect_success_total 13249
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 13482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 1915
telemt_me_reconnect_attempts_total 12275
telemt_me_reconnect_success_total 8842
telemt_me_reader_eof_total 9351
telemt_me_idle_close_by_peer_total 9350
telemt_me_route_drop_no_conn_total 219011
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521326
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
telemt_me_writer_removed_unexpected_total 9075
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8834
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 523259
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 5763339289 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 170115297912 (158.43 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 177602.0 (49h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3305508
telemt_connections_bad_total 31831
telemt_handshake_timeouts_total 221299
telemt_upstream_connect_attempt_total 39443
telemt_upstream_connect_success_total 39422
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10306
telemt_me_reconnect_attempts_total 35202
telemt_me_reconnect_success_total 30250
telemt_me_reader_eof_total 32110
telemt_me_idle_close_by_peer_total 32109
telemt_me_route_drop_no_conn_total 1133604
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2745670
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8998
telemt_desync_full_logged_total 3028
telemt_desync_suppressed_total 5970
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3260
telemt_desync_frames_bucket_total{bucket="gt_10"} 4226
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 30692
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30209
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 2744929
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 44686455988 (41.62 GB)
telemt_user_octets_to_client{user="hello"} 970219187889 (903.59 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 177604.4 (49h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2169894
telemt_connections_bad_total 22845
telemt_handshake_timeouts_total 225715
telemt_upstream_connect_attempt_total 55336
telemt_upstream_connect_success_total 52885
telemt_upstream_connect_fail_total 2314
telemt_upstream_connect_attempts_per_request{bucket="1"} 55062
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2313
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20345
telemt_me_reconnect_attempts_total 46025
telemt_me_reconnect_success_total 37005
telemt_me_reader_eof_total 39695
telemt_me_idle_close_by_peer_total 39688
telemt_me_route_drop_no_conn_total 758603
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1764237
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
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 37607
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36981
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 1770123
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 27325588263 (25.45 GB)
telemt_user_octets_to_client{user="hello"} 660840664602 (615.46 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47038.1 (13h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648793
telemt_connections_bad_total 7841
telemt_handshake_timeouts_total 6795
telemt_upstream_connect_attempt_total 10737
telemt_upstream_connect_success_total 10398
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 10737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 1434
telemt_me_reconnect_attempts_total 37737
telemt_me_reconnect_success_total 8019
telemt_me_reader_eof_total 9093
telemt_me_idle_close_by_peer_total 9092
telemt_me_route_drop_no_conn_total 246115
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604728
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1601
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1099
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9019
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 8014
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1000
telemt_user_connections_total{user="hello"} 604634
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 9672691784 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 198375934564 (184.75 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 38
```