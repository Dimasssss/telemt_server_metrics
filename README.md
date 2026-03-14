# Server Metrics 2026-03-14 05:54:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 172520.4 (47h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4865092
telemt_connections_bad_total 40023
telemt_handshake_timeouts_total 112440
telemt_upstream_connect_attempt_total 36292
telemt_upstream_connect_success_total 36055
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 7311
telemt_me_reconnect_attempts_total 35291
telemt_me_reconnect_success_total 25145
telemt_me_reader_eof_total 26989
telemt_me_idle_close_by_peer_total 26988
telemt_me_route_drop_no_conn_total 1841806
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4463735
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17164
telemt_desync_full_logged_total 4633
telemt_desync_suppressed_total 12531
telemt_desync_frames_bucket_total{bucket="1_2"} 4280
telemt_desync_frames_bucket_total{bucket="3_10"} 6561
telemt_desync_frames_bucket_total{bucket="gt_10"} 6323
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 25823
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25132
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 678
telemt_user_connections_total{user="hello"} 4465273
telemt_user_connections_current{user="hello"} 965
telemt_user_octets_from_client{user="hello"} 65301405012 (60.82 GB)
telemt_user_octets_to_client{user="hello"} 1408879483049 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72184.3 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787182
telemt_connections_bad_total 53075
telemt_handshake_timeouts_total 14535
telemt_upstream_connect_attempt_total 19747
telemt_upstream_connect_success_total 19477
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 19747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 2115
telemt_me_reconnect_attempts_total 17296
telemt_me_reconnect_success_total 13836
telemt_me_reader_eof_total 14711
telemt_me_idle_close_by_peer_total 14710
telemt_me_route_drop_no_conn_total 256571
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621641
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1855
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14135
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13828
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 623593
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 6611282273 (6.16 GB)
telemt_user_octets_to_client{user="hello"} 210093592564 (195.66 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 202141.0 (56h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3494697
telemt_connections_bad_total 38119
telemt_handshake_timeouts_total 230881
telemt_upstream_connect_attempt_total 45704
telemt_upstream_connect_success_total 45683
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10632
telemt_me_reconnect_attempts_total 40293
telemt_me_reconnect_success_total 35322
telemt_me_reader_eof_total 37525
telemt_me_idle_close_by_peer_total 37524
telemt_me_route_drop_no_conn_total 1194787
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2913107
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9610
telemt_desync_full_logged_total 3234
telemt_desync_suppressed_total 6376
telemt_desync_frames_bucket_total{bucket="1_2"} 1675
telemt_desync_frames_bucket_total{bucket="3_10"} 3474
telemt_desync_frames_bucket_total{bucket="gt_10"} 4461
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 35812
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35281
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 2912318
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 47396861888 (44.14 GB)
telemt_user_octets_to_client{user="hello"} 1042659938309 (971.05 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 202143.6 (56h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2339384
telemt_connections_bad_total 23161
telemt_handshake_timeouts_total 270258
telemt_upstream_connect_attempt_total 63118
telemt_upstream_connect_success_total 60636
telemt_upstream_connect_fail_total 2345
telemt_upstream_connect_attempts_per_request{bucket="1"} 62844
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2344
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20482
telemt_me_reconnect_attempts_total 52603
telemt_me_reconnect_success_total 43561
telemt_me_reader_eof_total 46707
telemt_me_idle_close_by_peer_total 46700
telemt_me_route_drop_no_conn_total 790882
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1850755
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3888
telemt_desync_full_logged_total 1255
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1046
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 44221
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43537
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1856752
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 28110148155 (26.18 GB)
telemt_user_octets_to_client{user="hello"} 681838300598 (635.01 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71577.2 (19h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763118
telemt_connections_bad_total 8030
telemt_handshake_timeouts_total 9017
telemt_upstream_connect_attempt_total 18483
telemt_upstream_connect_success_total 17992
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 18483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_timeout_total 1563
telemt_me_reconnect_attempts_total 56971
telemt_me_reconnect_success_total 14418
telemt_me_reader_eof_total 16103
telemt_me_idle_close_by_peer_total 16102
telemt_me_route_drop_no_conn_total 292846
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 712720
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1755
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1196
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15873
telemt_me_refill_failed_total 1325
telemt_me_writer_restored_same_endpoint_total 14413
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1455
telemt_user_connections_total{user="hello"} 712586
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 12737014980 (11.86 GB)
telemt_user_octets_to_client{user="hello"} 237864440580 (221.53 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 62
```